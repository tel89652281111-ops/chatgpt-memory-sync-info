# ChatGPT Memory Sync (personal)

A private automation used by its owner to request a ChatGPT data export, find the official export-ready email, and organize that export in the owner's Google Drive.

This is an independent personal tool, not an OpenAI or Google product. It is not offered as a public service.

## Privacy notice

The intended integration reads Gmail to locate official export notifications and uses Google Drive to maintain the owner's chat archive and selected memory files. Gmail access is read-only. The workflow does not send email.

Export processing runs in the owner's private GitHub Actions project. Credentials are stored as encrypted Actions secrets. Chat archives and conversation contents must not be committed to source repositories or retained in Actions logs, caches, or artifacts. Browser login state is held in the owner's TinyFish profile. Google Drive is the destination for the archive and memory files.

Data is used only to perform this user-requested workflow, not for advertising, sale, or training general-purpose AI models. Temporary downloaded archives are removed only after successful Drive verification. Existing archive-only folders are preserved.

The owner may stop scheduled jobs and revoke Google or TinyFish access at any time. Revoking access does not delete files already saved in Google Drive; the owner controls their retention directly in Drive.

This page contains no conversation contents, credentials, personal contact information, or private repository address.

Status: setup in progress; cloud scheduling is not yet enabled.
