.git/
├── HEAD            # Points to the current branch
├── config          # Repository-specific Git config
├── description     # Used mainly by GitWeb
├── index           # Staging area (binary file)
├── hooks/           # Client-side Git hooks (pre-commit, etc.)
├── info/
│   └── exclude     # Local ignore rules (like .gitignore but not shared)
├── objects/
│   ├── info/
│   └── pack/       # All Git objects (commits, trees, blobs)
└── refs/
    ├── heads/      # Local branches
    ├── tags/       # Tags
    └── remotes/    # Remote-tracking branches
