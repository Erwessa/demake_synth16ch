Add these files to the root of your repo (keep the folders), commit, push to main:
  .github/workflows/firmware.yml
  tools/fm1/get_toolchain.sh
  tools/fm1/get_sdk.sh
Then: Actions tab > Firmware > Run workflow (type the version) > open the finished run > Artifacts > demake-fwsc.
