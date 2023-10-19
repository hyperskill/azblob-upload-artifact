# azblob-upload-artifact
Hyperskill GitHub Action | Azure Blob upload artifacts

```yaml
- uses: hyperskill/azblob-upload-artifact@v1
  with:
    connection_string: ${{ secrets.AZURE_STORAGE_CONNECTION_STRING }}
    name: frontend-dist
    path: dist
```

For downloading, use https://github.com/marketplace/actions/download-artifacts
