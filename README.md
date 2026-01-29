<img src="aomedia_logo_rgb.svg" alt="Alliance for Open Media" width="280">

# AV2 Specification

This repository contains the **AV2 Bitstream & Decoding Process Specification** - the next-generation video coding specification from the Alliance for Open Media.


## About AV2

AV2 is the next-generation video coding specification developed by the Alliance for Open Media (AOM), building upon the success of AV1. Designed to deliver significantly improved compression efficiency, AV2 targets applications requiring high-quality video at lower bitrates, including streaming, broadcasting, and video conferencing.

Key improvements over AV1 include enhanced coding tools, improved compression efficiency, and support for advanced features such as multi-layer coding and extended color formats.

**Note**: This is a draft specification release. Known issues and planned improvements are documented in the [Release Notes](./v13_release_notes.pdf).

## Available Versions

### v13 (Draft Release)

The current draft release is available in the `v13-public/` directory:

- **[Full Specification](v13-public/index.html)** - Complete specification document with all sections (Syntax, Semantics, Decoding Process, Tables, Annexes)
- **[Syntax Browser](v13-public/syntax_browser.html)** - Interactive split-pane view of Sections 5 & 6 with synchronized navigation
- **[Attachments](v13-public/attachments/)** - Section 9 lookup tables as C header files
- **[Release Notes](./v13_release_notes.pdf)** - Known issues and planned improvements

## Reference Software

The AVM reference software implementation corresponding to this specification is available on GitLab:

**[AVM v13.0.0](https://gitlab.com/AOMediaCodec/avm/-/tree/research-v13.0.0?ref_type=tags)**

For issues with the reference software, please use the [GitLab issue tracker](https://gitlab.com/AOMediaCodec/avm/-/issues).

## Providing Feedback

We welcome feedback on the specification! Please use our GitHub issue templates to report problems or ask questions:

- **[Technical Issue](https://github.com/AOMediaCodec/av2-spec/issues/new?template=technical-issue.yml)** - Errors, ambiguities, or missing information in the spec
- **[Editorial Issue](https://github.com/AOMediaCodec/av2-spec/issues/new?template=editorial-issue.yml)** - Typos, formatting, or consistency issues
- **[Clarification Request](https://github.com/AOMediaCodec/av2-spec/issues/new?template=clarification-request.yml)** - Questions about interpretation or implementation
- **[Syntax Browser Issue](https://github.com/AOMediaCodec/av2-spec/issues/new?template=syntax-browser-issue.yml)** - Issues with the syntax browser tool

**Before submitting**: Please search [existing issues](https://github.com/AOMediaCodec/av2-spec/issues) and check the [Release Notes](index.html#release-notes) for known issues.

**Note**: This repository contains compiled specification outputs only. Responses may be limited as work continues toward the final AV2 specification release.

## Repository Structure

```
av2-spec/
├── index.html              # Landing page with version links and release notes
├── aomedia_logo_rgb.svg    # AOM logo
├── v13_release_notes.pdf   # Release notes (PDF)
├── v13-public/             # v13 draft specification
│   ├── index.html          # Full specification document
│   ├── syntax_browser.html # Interactive syntax/semantics browser
│   ├── attachments/        # Section 9 tables as .h files
│   ├── css/                # Stylesheets
│   ├── js/                 # JavaScript
│   └── images/             # Figures and diagrams
└── LICENSE                 # License information
```

## License

See the [LICENSE](./LICENSE) file for licensing information.

## Resources

- **Alliance for Open Media**: [https://aomedia.org](https://aomedia.org)
- **AVM Reference Software**: [https://gitlab.com/AOMediaCodec/avm](https://gitlab.com/AOMediaCodec/avm)
- **AV1 Specification**: [https://aomediacodec.github.io/av1-spec/](https://aomediacodec.github.io/av1-spec/)
