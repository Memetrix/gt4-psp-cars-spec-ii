# Install the patch

You need your own clean ISO of **Gran Turismo 4 Spec II v1.10 (NTSC-U)**
(MD5 `2c89bc11ccf68dc68f8af39c9e75096a`) and the `.xdelta` file of the release.

1. Download [Delta Patcher for Windows or macOS](https://github.com/marco-calautti/DeltaPatcher/releases).
2. Make a copy of your clean ISO. In Delta Patcher, select that copy as
   **Original file** and the `.xdelta` as **XDelta patch**.
3. Leave checksum validation on and click **Apply patch**. Delta Patcher updates
   the selected copy; your original ISO remains unchanged.

The patched ISO (v1.0.1) has SHA-256
`f371892ef1a99fd58f2f9a2754ba26e1fcb8fa0f29fbcfd90287657881679916`.

**Updating from v1.0.0:** apply v1.0.1 to a fresh copy of the clean ISO. It does not apply to an ISO
already patched with v1.0.0. Game saves carry over.

If the patch fails, check the MD5 of the original ISO. An ISO from another region, another Spec II version,
vanilla GT4, the Online Public Beta or a previously modified image is a different input: this patch does not
apply to it. The download contains the patch only, not game files.
