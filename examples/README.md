# Go SDK examples

1. From repo root: `make merge-custom` (or `make sdk-all` / `make go-sdk` so `api/go` exists and custom files are merged).
2. Copy `.env.sample` to `.env` and set **`TIRDAD_API_KEY`**. Optionally set **`TIRDAD_API_HOST`** to your API base URL (default in sample: `https://api.tirdad.ai/v1`).
3. From **`api/go/examples`**: `go mod tidy && go run .`

This sample creates a customer, ingests one event (sync), then enqueues via the **custom async client** (`NewAsyncClientWithConfig`). Custom SDK files live in `api/custom/go/`.

**Integration tests:** Full API flows use a different env shape (host without scheme); see [api/tests/go/test_sdk.go](../../tests/go/test_sdk.go) and [api/tests/README.md](../../tests/README.md).
