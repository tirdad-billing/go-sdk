# SecretProvider

## Example Usage

```go
import (
	"github.com/tirdad-billing/go-sdk/v2/models/types"
)

value := types.SecretProviderTirdad

// Open enum: custom values can be created with a direct type cast
custom := types.SecretProvider("custom_value")
```


## Values

| Name                       | Value                      |
| -------------------------- | -------------------------- |
| `SecretProviderTirdad`  | tirdad                  |
| `SecretProviderStripe`     | stripe                     |
| `SecretProviderS3`         | s3                         |
| `SecretProviderHubspot`    | hubspot                    |
| `SecretProviderRazorpay`   | razorpay                   |
| `SecretProviderChargebee`  | chargebee                  |
| `SecretProviderQuickbooks` | quickbooks                 |
| `SecretProviderZohoBooks`  | zoho_books                 |
| `SecretProviderNomod`      | nomod                      |
| `SecretProviderMoyasar`    | moyasar                    |
| `SecretProviderPaddle`     | paddle                     |
| `SecretProviderWhop`       | whop                       |
| `SecretProviderTabs`       | tabs                       |