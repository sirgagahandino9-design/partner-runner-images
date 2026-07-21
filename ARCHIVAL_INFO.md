# Repository Archival Information

**Archival Date:** June 12, 2026

---

## Quick Links

| Resource | Link |
|----------|------|
| **New Repository** | [actions/runner-images](https://github.com/actions/runner-images) |
| **Support** | [SUPPORT.md](SUPPORT.md) |
| **Security** | [SECURITY.md](SECURITY.md) |
| **Contributing** | [CONTRIBUTING.md](CONTRIBUTING.md) |
| **Changelog** | [CHANGELOG.md](CHANGELOG.md) |

---

## What Happened

### Timeline

- **October 2023:** Arm-based runner images first available via partnership with Arm Limited
- **June 12, 2026:** GitHub assumes full ownership; this repository is archived
- **Now:** All new development happens in [actions/runner-images](https://github.com/actions/runner-images)

### Why This Change

GitHub has integrated Arm64 support directly into the main Actions infrastructure, eliminating the need for a separate partner repository. This provides:

✅ Better integration with GitHub Actions
✅ Unified support and maintenance
✅ Faster updates and security patches
✅ Simplified documentation and workflows

---

## What Remains Available

### Images

All three Arm-based images remain fully available and supported:

| Image | YAML Label | Status |
|-------|-----------|--------|
| Ubuntu 24.04 | `ubuntu-24.04-arm` | ✅ Available |
| Ubuntu 22.04 | `ubuntu-22.04-arm` | ✅ Available |
| Windows 11 | `windows-11-arm` | ✅ Available |

### Image Documentation

Complete software inventories for each image are available in the `/images` directory:

- [Ubuntu 24.04 Inventory](/images/arm-ubuntu-24-image.md)
- [Ubuntu 22.04 Inventory](/images/arm-ubuntu-22-image.md)
- [Windows 11 Inventory](/images/arm-windows-11-image.md)

Detailed generated readmes:

- [Ubuntu 24.04 Readme](/images/Ubuntu2404-Readme.md)
- [Ubuntu 22.04 Readme](/images/Ubuntu2204-Readme.md)

---

## Migration Guide

### For Users (No Action Required)

✅ Your existing workflows will continue to work exactly as they do now

### For Issue Reporters

**Old Process:**
- Report issues here: https://github.com/actions/partner-runner-images/issues

**New Process:**
- Report issues here: https://github.com/actions/runner-images/issues
- Include the image name and version
- Existing issues are being migrated automatically

### For Contributors

**Old Process:**
- Contribute to this repository

**New Process:**
- Contribute to [actions/runner-images](https://github.com/actions/runner-images)
- See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines

### For Support

**Old Process:**
- Ask here: https://github.com/actions/partner-runner-images/issues

**New Process:**
- GitHub Support: https://support.github.com
- Community: https://github.com/orgs/community/discussions
- Issues: https://github.com/actions/runner-images/issues

---

## Archive Contents

This repository archive contains:

### Documentation
- `README.md` - Overview and archival notice
- `SUPPORT.md` - Support and help information
- `SECURITY.md` - Security policy and vulnerability reporting
- `CONTRIBUTING.md` - Contribution guidelines (now deprecated)
- `CHANGELOG.md` - Release notes and archival information
- `ARCHIVAL_INFO.md` - This file

### Image Documentation
- `/images/` - Complete software inventory for each image
  - `arm-ubuntu-24-image.md` - Ubuntu 24.04 Arm image details
  - `arm-ubuntu-22-image.md` - Ubuntu 22.04 Arm image details
  - `arm-windows-11-image.md` - Windows 11 Arm image details
  - `Ubuntu2404-Readme.md` - Auto-generated Ubuntu 24.04 inventory
  - `Ubuntu2204-Readme.md` - Auto-generated Ubuntu 22.04 inventory

### GitHub Configuration
- `.github/ISSUE_TEMPLATE/` - Issue templates with archival notices
- `.github/workflows/` - Workflow examples with archival notices
- `.github/CODEOWNERS` - Repository ownership information

---

## Frequently Asked Questions

### Q: Will my workflows break after archival?

**A:** No. The Arm-based images remain fully functional and available. Your workflows will continue to work without any changes required.

### Q: Where do I report bugs?

**A:** Please report bugs in [actions/runner-images](https://github.com/actions/runner-images/issues). Existing issues from this repository are being migrated.

### Q: Can I still request new tools?

**A:** Yes! Please create an issue in [actions/runner-images](https://github.com/actions/runner-images/issues) with your request.

### Q: What happens to issues reported here?

**A:** All issues are being migrated to [actions/runner-images](https://github.com/actions/runner-images). You'll see them there with references back to the original.

### Q: Is this repository read-only now?

**A:** Yes, this repository is archived and read-only. All new issues and pull requests should be directed to [actions/runner-images](https://github.com/actions/runner-images).

### Q: Where can I find image documentation?

**A:** 
- In this repository: `/images/` directory (archived)
- In the new repository: [actions/runner-images](https://github.com/actions/runner-images)

### Q: How do I update my workflows to use the new repository?

**A:** You don't need to! The image labels (`ubuntu-24.04-arm`, `ubuntu-22.04-arm`, `windows-11-arm`) remain the same and continue to work.

### Q: Is there a difference in support for Arm images now?

**A:** Better! Arm images are now fully integrated into GitHub's official runner images repository, ensuring better support and faster updates.

---

## Resources

### Official Documentation
- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Runner Images Repository](https://github.com/actions/runner-images)
- [GitHub Hosted Runners](https://docs.github.com/en/actions/using-github-hosted-runners/about-github-hosted-runners)

### Community
- [GitHub Community Discussions](https://github.com/orgs/community/discussions/categories/actions)
- [GitHub Support](https://support.github.com)

### Images
- [Ubuntu 24.04 on Arm64](https://github.com/actions/runner-images/tree/main/images/ubuntu)
- [Windows 11 on Arm64](https://github.com/actions/runner-images/tree/main/images/windows)

---

## Acknowledgments

This repository served as an important stepping stone in bringing Arm-based CI/CD to GitHub Actions. Special thanks to:

- **Arm Limited, Inc.** - For developing and maintaining the Arm-based images
- **GitHub Actions Team** - For integrating and maintaining Arm support
- **Community Users** - For feedback, bug reports, and support

The transition to GitHub ownership ensures continued support and innovation for Arm-based CI/CD workflows.

---

## Archive Snapshot

**Last Update:** June 12, 2026
**Repository Status:** Archived (Read-Only)
**Issues:** Being migrated to [actions/runner-images](https://github.com/actions/runner-images)
**Pull Requests:** Not accepted (archive is read-only)

For the latest information, visit [actions/runner-images](https://github.com/actions/runner-images).
