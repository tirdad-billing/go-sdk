<!-- Start SDK Example Usage [usage] -->
```go
package main

import (
	"context"
	tirdad "github.com/tirdad-billing/go-sdk/v2"
	"github.com/tirdad-billing/go-sdk/v2/models/types"
	"log"
)

func main() {
	ctx := context.Background()

	s := tirdad.New(
		tirdad.WithSecurity("<YOUR_API_KEY_HERE>"),
	)

	res, err := s.Addons.CreateAddon(ctx, types.CreateAddonRequest{
		LookupKey: "<value>",
		Name:      "<value>",
	})
	if err != nil {
		log.Fatal(err)
	}
	if res.CreateAddonResponse != nil {
		// handle response
	}
}

```
<!-- End SDK Example Usage [usage] -->