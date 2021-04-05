<!-- #include "./common/header.md" -->

# Add-VSTeamAzureRMServiceEndpoint

## SYNOPSIS

<!-- #include "./synopsis/Add-VSTeamAzureRMServiceEndpoint.md" -->

## SYNTAX

## DESCRIPTION

The cmdlet adds a new connection between TFS/AzD and Azure using the Azure Resource Manager connection type.

## EXAMPLES

### Example 1

```powershell
Add-VSTeamAzureRMServiceEndpoint -subscriptionName "MySubscription" -subscriptionId "f26125aa-e373-496e-8b5f-8c0dbf4758cf" -subscriptionTenantId "0a15879c-7b74-4263-a2bb-09a2652b183a" -servicePrincipalId "9d24b8ff-0e73-4bcf-86b2-90fbc705974a" -servicePrincipalKey "+&UZRZ%WJ.tejzret$&IE%§UWJTEEE&,W5u3jesr" -endpointName "My Azure Endppoint"
```

It creates and Azure Resource Manager service endpoint to the subscription MySubscription(f26125aa-e373-496e-8b5f-8c0dbf4758cf) in the Azure AD tenant '0a15879c-7b74-4263-a2bb-09a2652b183a'. For the connection the service principal '9d24b8ff-0e73-4bcf-86b2-90fbc705974a' is being used. The end point display name is 'My Azure Endppoint'

## PARAMETERS

### SubscriptionName

The name of the Azure Subscription.

```yaml
Type: String
Aliases: displayName
Required: True
Position: 1
Accept pipeline input: true (ByPropertyName)
```

### SubscriptionId

The id of the Azure subscription to use.

```yaml
Type: String
Required: True
Position: 2
Accept pipeline input: true (ByPropertyName)
```

### SubscriptionTenantId

The id of the Azure tenant to use.

```yaml
Type: String
Required: True
Position: 3
Accept pipeline input: true (ByPropertyName)
```

### ServicePrincipalId

The ID of the Azure Service Principal to use with this service endpoint.

```yaml
Type: String
Parameter Sets: Manual
Required: True
Accept pipeline input: true (ByPropertyName)
```

### ServicePrincipalKey

The key of the Azure Service Principal to use with this service endpoint.

```yaml
Type: String
Parameter Sets: Manual
Required: True
Accept pipeline input: true (ByPropertyName)
```

### EndpointName

The name displayed on the services page.
In AzD this is the Connection Name.

```yaml
Type: String
Position: 4
```

<!-- #include "./params/projectName.md" -->

## INPUTS

## OUTPUTS

## NOTES

<!-- #include "./common/prerequisites.md" -->

## RELATED LINKS

<!-- #include "./common/related.md" -->

[Get-VSTeamServiceEndpoint](Get-VSTeamServiceEndpoint.md)

[Get-VSTeamServiceEndpointType](Get-VSTeamServiceEndpointType.md)

[Remove-VSTeamServiceEndpoint](Remove-VSTeamServiceEndpoint.md)
