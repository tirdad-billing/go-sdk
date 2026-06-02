# S3ExportConfig


## Fields

| Field                                                                  | Type                                                                   | Required                                                               | Description                                                            |
| ---------------------------------------------------------------------- | ---------------------------------------------------------------------- | ---------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| `Bucket`                                                               | `*string`                                                              | :heavy_minus_sign:                                                     | S3 bucket name                                                         |
| `Compression`                                                          | [*types.S3CompressionType](../../models/types/s3compressiontype.md)    | :heavy_minus_sign:                                                     | N/A                                                                    |
| `Encryption`                                                           | [*types.S3EncryptionType](../../models/types/s3encryptiontype.md)      | :heavy_minus_sign:                                                     | N/A                                                                    |
| `IsTirdadManaged`                                                   | `*bool`                                                                | :heavy_minus_sign:                                                     | If true, use Tirdad-managed S3 credentials instead of user-provided |
| `KeyPrefix`                                                            | `*string`                                                              | :heavy_minus_sign:                                                     | Optional prefix for S3 keys (e.g., "flexprice-exports/")               |
| `Region`                                                               | `*string`                                                              | :heavy_minus_sign:                                                     | AWS region (e.g., "us-west-2")                                         |