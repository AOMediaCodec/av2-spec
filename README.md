<img src="aomedia_logo_rgb.svg" alt="Alliance for Open Media" width="280">

# AV2 Specification

This repository contains the **AV2 Bitstream & Decoding Process Specification** - the next-generation video coding specification from the Alliance for Open Media.


## About AV2

AV2 is the next-generation video coding specification developed by the Alliance for Open Media (AOM), building upon the success of AV1. Designed to deliver significantly improved compression efficiency, AV2 targets applications requiring high-quality video at lower bitrates, including streaming, broadcasting, and video conferencing.

Key improvements over AV1 include enhanced coding tools, improved compression efficiency, and support for advanced features such as multi-layer coding and extended color formats.

## Available Versions

### v1.0.0 (Current Release)

The official public release is available in the `v1.0.0/` directory:

- **[Full Specification (HTML)](v1.0.0/index.html)** - Complete specification document with all sections (Syntax, Semantics, Decoding Process, Tables, Annexes)
- **[Full Specification (PDF)](v1.0.0/20260528_38f28e7_AV2_Spec_v1.0.0.pdf)** - The complete specification as a downloadable PDF
- **[Syntax Browser](v1.0.0/syntax_browser.html)** - Interactive split-pane view of Sections 5 & 6 with synchronized navigation
- **[Additional Tables](v1.0.0/attachments/)** - Section 9 lookup tables as C header files

### v13 (Superseded Working Draft)

An earlier development draft, retained for reference in the `v13-public/` directory. The "v13" label denotes a working-draft milestone and does **not** indicate a version newer than 1.0.0.

- **[Full Specification](v13-public/index.html)** - Complete specification document
- **[Syntax Browser](v13-public/syntax_browser.html)** - Interactive split-pane view of Sections 5 & 6
- **[Additional Tables](v13-public/attachments/)** - Section 9 lookup tables as C header files
- **[Release Notes](v13-public/v13_release_notes.pdf)** - Known issues and planned improvements for the v13 draft

## Reference Software

The AVM reference software implementation corresponding to v1.0.0 is available on GitHub:

**[AVM v1.0.0](https://github.com/AOMediaCodec/avm/tree/v1.0.0)**

For issues with the reference software, please use the [GitHub issue tracker](https://github.com/AOMediaCodec/avm/issues).

## Providing Feedback

We welcome feedback on the specification! Please send your comments, questions, or issue reports to:

**[wg-codec-chair@aomedia.org](mailto:wg-codec-chair@aomedia.org)**

or file an issue on the **[AVM issue tracker](https://github.com/AOMediaCodec/avm/issues)**.

When reporting issues, please include:
- Section number or specific location
- Clear description of the issue or question

**Note**: This repository contains compiled specification outputs only.

## Repository Structure

```
av2-spec/
├── index.html              # Landing page with version links
├── aomedia_logo_rgb.svg    # AOM logo
├── av2-logo.svg            # AV2 logo
├── v1.0.0/                 # v1.0.0 release (current)
│   ├── index.html          # Full specification document
│   ├── *.pdf               # Full specification as PDF
│   ├── syntax_browser.html # Interactive syntax/semantics browser
│   ├── attachments/        # Section 9 tables as .h files
│   ├── css/                # Stylesheets
│   ├── js/                 # JavaScript
│   └── images/             # Figures and diagrams
├── v13-public/             # v13 superseded working draft
│   ├── v13_release_notes.pdf  # Release notes for the v13 draft (PDF)
│   └── ...                 # Same structure as v1.0.0 (no spec PDF)
└── LICENSE                 # License information
```

## License

See the [LICENSE](./LICENSE) file for licensing information.

## Resources

- **Alliance for Open Media**: [https://aomedia.org](https://aomedia.org)
- **AVM Reference Software**: [https://github.com/AOMediaCodec/avm](https://github.com/AOMediaCodec/avm)
- **AV1 Specification**: [https://aomediacodec.github.io/av1-spec/](https://aomediacodec.github.io/av1-spec/)
