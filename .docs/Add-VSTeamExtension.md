<!-- #include "./common/header.md" -->

# Add-VSTeamExtension

## SYNOPSIS

<!-- #include "./synopsis/Add-VSTeamExtension.md" -->

## SYNTAX

## DESCRIPTION

<!-- #include "./synopsis/Add-VSTeamExtension.md" -->

## EXAMPLES

### Example 1

```powershell
Add-VSTeamExtension -PublisherId "MyUniquePublisher" -ExtensionId "vsteam-build-release-and-run"
```

Installs the extension 'vsteam-build-release-and-run' of the publisher -PublisherId 'MyUniquePublisher' with the latest version.

### Example 2

```powershell
Add-VSTeamExtension -PublisherId "MyUniquePublisher" -ExtensionId "vsteam-build-release-and-run" -Version 1.0.4
```

Installs the extension 'vsteam-build-release-and-run' of the publisher -PublisherId 'MyUniquePublisher' with the version '1.0.4'.

## PARAMETERS

### PublisherId

The id of the publisher.

```yaml
Type: String
Required: True
```

### ExtensionId

The id of the extension.

```yaml
Type: String
Required: True
```

### Version

The version of the extension. Example: "0.1.35".

```yaml
Type: String
Required: False
```

## INPUTS

## OUTPUTS

## NOTES

<!-- #include "./common/prerequisites.md" -->

## RELATED LINKS

<!-- #include "./common/related.md" -->

[Add-VSTeamExtension](Add-VSTeamExtension.md)

[Get-VSTeamExtension](Get-VSTeamExtension.md)

[Remove-VSTeamExtension](Remove-VSTeamExtension.md)

[Update-VSTeamExtension](Update-VSTeamExtension.md)
