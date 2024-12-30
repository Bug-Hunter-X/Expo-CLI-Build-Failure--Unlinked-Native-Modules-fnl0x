# Expo CLI Build Failure: Unlinked Native Modules

This repository demonstrates a common issue encountered when using the Expo CLI with packages containing native modules.  The problem stems from incomplete linking of these native modules, resulting in build failures or runtime crashes. The `expoBug.js` file showcases the problematic code, while `expoBugSolution.js` offers a solution.

**Problem:** The Expo CLI does not automatically link native modules in some cases.  The error may manifest as an obscure message during the build process or as an app crash at runtime.

**Solution:**  The solution involves using the correct linking mechanisms provided by Expo or the package in question. This often means explicitly linking native modules or utilizing Expo's managed workflow properly.