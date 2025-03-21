## Upstash Ratelimit Plugin Privacy Policy
This privacy policy explains how the Upstash Ratelimit plugin collects, uses, and processes user data. Please read this policy carefully before using the plugin.

### Data Collection and Usage
The Upstash Rate Limit Plugin does not collect, store, or process any direct identifier user data. This plugin solely integrates Upstash Redis-based rate limiting with the Dify AI platform.

The plugin requires Upstash Redis REST URL and Token for authentication purposes only. These indirect identifiers are processed as Dify `secret-input` credentials and are stored only within your Dify instance.

However, if the "Rate Limit Scope" parameter is set to "Per User", the Dify-provided `sys.user_id` is used as an identifier to enforce rate limiting. This identifier is stored in Upstash Redis temporarily and can be viewed through the Upstash Redis monitor during that period. The Upstash Rate Limit Plugin does not process or retain this data internally. It is only used to distinguish different user requests.

### Use of Third-Party Services
This plugin requires an Upstash Redis instance for functionality.
- **Upstash’s Privacy Policy** can be found at [here](https://upstash.com/trust/privacy.pdf).

This plugin does not share your data with any third parties beyond those mentioned above.

### Security
The plugin does not store any personally identifiable information of plugin users.
Data is only temporarily stored for processing purposes when necessary.

### Contact Information
If you have any questions regarding this privacy policy, please contact the plugin author.

Last Updated: March 2025