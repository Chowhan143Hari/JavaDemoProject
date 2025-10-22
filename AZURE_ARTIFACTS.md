
# Azure Artifacts Setup

1. Create a feed in Azure Artifacts.
2. Configure Maven to use the feed:

```
<repositories>
  <repository>
    <id>azure-artifacts</id>
    <url>https://pkgs.dev.azure.com/your-org/_packaging/your-feed/maven/v1</url>
  </repository>
</repositories>
```
3. Publish using Maven deploy plugin.
