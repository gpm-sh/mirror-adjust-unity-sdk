# Adjust Unity SDK — GPM Mirror

This is a **mirror** of the [Adjust Unity SDK](https://github.com/adjust/unity_sdk) maintained by [GPM.sh](https://gpm.sh).

- **License:** MIT (see LICENSE in upstream)
- **Modifications by GPM:**  
  - Added `.asmdef` files  
  - Converted to UPM package structure  
  - Added package.json metadata  

## Install (UPM)

```json
{
  "scopedRegistries": [
    {
      "name": "GPM",
      "url": "https://registry.gpm.sh"
    }
  ],
  "dependencies": {
    "com.adjust.unity": "5.0.2-gpm.1"
  }
}
