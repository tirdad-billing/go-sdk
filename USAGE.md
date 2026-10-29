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

	res, err := s.AccountingPeriods.QueryAccountingPeriod(ctx, types.AccountingperiodFilter{})
	if err != nil {
		log.Fatal(err)
	}
	if res.ListAccountingPeriodsResponse != nil {
		// handle response
	}
}

```
<!-- End SDK Example Usage [usage] -->