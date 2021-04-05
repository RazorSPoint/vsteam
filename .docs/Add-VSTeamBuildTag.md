<!-- #include "./common/header.md" -->

# Add-VSTeamBuildTag

## SYNOPSIS

<!-- #include "./synopsis/Add-VSTeamBuildTag.md" -->

## SYNTAX

## DESCRIPTION

Adds a tag to a build.

## EXAMPLES

### Example 1

```powershell
Add-VSTeamBuildTag -ProjectName 'MyProject' -id 2 -Tags @("Tag1", "Tag2", "Tag3")
```

Adds the tags Tag1, Tag2 and Tag3 to the build with the id 2.

## PARAMETERS

<!-- #include "./params/buildIds.md" -->

<!-- #include "./params/buildTags.md" -->

<!-- #include "./params/projectName.md" -->

<!-- #include "./params/forcegroup.md" -->

## INPUTS

## OUTPUTS

### System.Object

## NOTES

<!-- #include "./common/prerequisites.md" -->

## RELATED LINKS

<!-- #include "./common/related.md" -->
