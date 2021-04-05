<!-- #include "./common/header.md" -->

# Add-VSTeamGitRepositoryPermission

## SYNOPSIS

<!-- #include "./synopsis/Add-VSTeamGitRepositoryPermission.md" -->

## SYNTAX

## DESCRIPTION

<!-- #include "./synopsis/Add-VSTeamGitRepositoryPermission.md" -->

## EXAMPLES

### Example 1

```powershell
Add-VSTeamGitRepositoryPermission -Project MyProject -RepositoryName MyRepo -BranchName main -Group $myGroup -Allow GenericRead -Deny Administer
```

Sets permission of branch 'main' to allow read and deny administer permission. Group object is given do apply permissions to.

### Example 2

```powershell
Add-VSTeamGitRepositoryPermission -Project MyProject -User $myGroup -Allow GenericRead -Deny Administer
```

Sets permission of all repositories on project level to allow read and deny administer permission. User object is given do apply permissions to.

## PARAMETERS

### RepositoryId

```yaml
Type: String
Required: True
```

### RepositoryName

```yaml
Type: String
Required: True
```

### BranchName

```yaml
Type: String
Required: True
```

### Descriptor

```yaml
Type: String
Required: True
```

### User

```yaml
Type: VSTeamUser
Required: True
```

### Group

```yaml
Type: VSTeamGroup
Required: True
```

### Allow

```yaml
Type: VSTeamGitRepositoryPermissions
Required: True
```

### Deny

```yaml
Type: VSTeamGitRepositoryPermissions
Required: True
```

<!-- #include "./params/projectName.md" -->

## INPUTS

## OUTPUTS

### System.Object

## NOTES

<!-- #include "./common/prerequisites.md" -->

## RELATED LINKS

<!-- #include "./common/related.md" -->
