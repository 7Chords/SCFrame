# SCFrame

UPM package source for the SCFrame Unity framework.

- Package name: `com.7chords.scframe`
- Package root: `Assets/_Scripts/SCFrame`
- Local development project: `F:/UnityProjects/Dev_GameFrame`
- Remote: `https://github.com/7Chords/SCFrame`

## Consume in another project

Use a local path while developing:

```json
"com.7chords.scframe": "file:F:/UnityProjects/Dev_GameFrame/Assets/_Scripts/SCFrame"
```

Or use the Git package after the package manifest is pushed:

```json
"com.7chords.scframe": "https://github.com/7Chords/SCFrame.git?path=Assets/_Scripts/SCFrame#main"
```

The Git URL requires `package.json` to be committed on the target branch.

## Development

Edit the framework in `Dev_GameFrame`, then commit and push the `SCFrame` folder. Consumers can re-resolve the package or use the Git URL to pick up the new revision.
