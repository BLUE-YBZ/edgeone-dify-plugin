# Privacy Policy

## Data Collection

The EdgeOne Pages plugin is designed with privacy in mind and follows data minimization principles:

### Personal Data Collection
- **No Personal Information Stored**: This plugin does not collect, store, or process any personal user information
- **No User Tracking**: We do not track user behavior, usage patterns, or personal identifiers
- **No Analytics**: The plugin does not implement any analytics or telemetry systems

### Technical Data Processed
The plugin only processes technical data necessary for its core functionality:

1. **HTML Content**: HTML code provided by users for deployment (processed temporarily, not stored)
2. **ZIP Files**: Website files uploaded by users (processed temporarily, not stored)
3. **API Credentials**: EdgeOne API tokens provided by users (encrypted and stored securely within Dify)
4. **Project Names**: Optional EdgeOne project names (stored locally within Dify configuration)

## Data Processing

### How We Handle Your Data

**HTML Deployment:**
- HTML content is sent directly to EdgeOne Pages service via secure HTTPS connection
- Content is not logged, cached, or stored by the plugin
- Content becomes publicly accessible via EdgeOne's global CDN as intended

**ZIP File Deployment:**
- ZIP files are temporarily downloaded from Dify's file system
- Files are uploaded directly to EdgeOne COS (Cloud Object Storage) via secure connection
- Temporary files are immediately deleted after successful upload
- No file content is retained by the plugin

**API Credentials:**
- EdgeOne API tokens are encrypted and stored within Dify's secure credential management system
- Tokens are only used for authentication with EdgeOne services
- Plugin does not have access to decrypt or export stored credentials

### Data Retention
- **No Data Retention**: The plugin does not retain any user data beyond the temporary processing period
- **Immediate Cleanup**: All temporary files and processing data are deleted immediately after completion
- **Credential Storage**: API credentials are managed entirely by Dify's secure credential system

## Third-Party Services

This plugin integrates with the following third-party services:

### EdgeOne Pages (Tencent Cloud)
- **Service**: EdgeOne Pages platform for web hosting and CDN
- **Data Shared**: HTML content, ZIP files, API authentication tokens
- **Purpose**: To deploy and serve user content via EdgeOne's global edge network
- **Privacy Policy**: [Tencent Cloud Privacy Policy](https://intl.cloud.tencent.com/document/product/301/17345)
- **Security**: All data transmission uses HTTPS encryption

### EdgeOne API Endpoints
- **Service**: EdgeOne API for project management and deployment
- **Data Shared**: API tokens, project metadata, deployment configurations
- **Purpose**: To manage EdgeOne projects and deployments programmatically
- **Security**: API communications use bearer token authentication over HTTPS

## Data Security

### Security Measures
- **Encryption in Transit**: All API communications use HTTPS/TLS encryption
- **No Local Storage**: Plugin does not store any user data on local file systems
- **Secure Credential Handling**: API tokens are managed by Dify's encrypted credential system
- **Temporary File Cleanup**: All temporary files are securely deleted after processing

### Access Controls
- **Principle of Least Privilege**: Plugin only requests necessary permissions for deployment functionality
- **No Unauthorized Access**: Plugin cannot access user data outside of explicitly provided deployment content
- **Secure Token Usage**: API tokens are only used for intended EdgeOne API calls

## User Rights

### Your Data Rights
- **Access**: Users can view their stored API credentials within Dify settings
- **Modification**: Users can update or change their EdgeOne API credentials at any time
- **Deletion**: Users can remove their API credentials from the plugin configuration
- **Portability**: No user data is locked within the plugin system

### Content Control
- **Deployment Control**: Users have full control over what content is deployed
- **Environment Selection**: Users can choose deployment environments (Production/Preview)
- **Content Management**: All deployed content can be managed through EdgeOne console

## Compliance

### Data Protection Standards
- **GDPR Compliance**: Plugin design follows GDPR principles of data minimization and purpose limitation
- **No Cross-Border Data Issues**: Data is only transmitted to user-specified EdgeOne regions
- **Consent-Based Processing**: All data processing requires explicit user action (deployment requests)

### Business Use
- **Enterprise Safe**: Plugin is suitable for enterprise use with appropriate security controls
- **Audit Trail**: All deployment actions are logged within Dify's standard logging system
- **Compliance Support**: Plugin design supports organizational data governance requirements

## Contact Information

### Privacy Inquiries
For questions about this privacy policy or data handling practices:
- **GitHub Issues**: Report privacy concerns via repository issues
- **Community Forums**: General questions via Dify community channels

### Service Provider Contact
For EdgeOne service-related privacy questions:
- **EdgeOne Support**: Contact Tencent Cloud EdgeOne support team
- **EdgeOne Privacy**: Refer to Tencent Cloud privacy documentation

## Policy Updates

### Version History
- **Version 1.0**: Initial privacy policy (December 2024)

### Change Notification
- Users will be notified of any privacy policy changes through plugin update notes
- Material changes will be clearly highlighted in release documentation
- Continued use of the plugin constitutes acceptance of updated privacy terms

### Review Schedule
- This privacy policy is reviewed and updated as needed with each major plugin release
- Annual review to ensure continued compliance with privacy regulations

---

**Last Updated**: December 2024  
**Policy Version**: 1.0  
**Plugin Version**: 0.0.1

---

*This privacy policy is specific to the EdgeOne Pages Dify plugin. For Dify platform privacy policies, please refer to Dify's official privacy documentation. For EdgeOne service privacy policies, please refer to Tencent Cloud's privacy documentation.*