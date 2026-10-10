⚡️ NEXUS YAML VERIFIER — Predict GitHub Actions failures before they run
Version License Python Status
Real test for GitHub Actions workflows. Know if your workflow will PASS or FAIL — before you push.
🎯 What is it?
NEXUS YAML VERIFIER is a live dashboard + real execution engine for GitHub Actions workflows.
It doesn't just parse YAML. It runs the logic and tells you:
✅ Will the workflow succeed?
❌ Will it fail? At which step?
⏱️ How long will it take (in ms)?
🔐 Is the file signed and verified?
Real test. Real execution. Real result.
Built for teams who can't afford a broken CI/CD pipeline.
🔥 Features
Feature Description
🌐 Live Dashboard HTTP server on port 8877 with real-time stats
🔗 GitHub API Load any repo, list workflows, test them all
📋 YAML Validation Syntax + structure + security checks
▶️ Real Execution Test Know if it PASSES or FAILS before you push
⏱️ Duration Report How long each workflow takes (ms)
🔐 HMAC + SHA-256 Every file is signed and verified
💾 SQLite History Full audit trail of every scan
📤 Export JSON/CSV Reports ready for CI/CD integration
🎯 Score System 0-100 quality score per workflow
🛡 Security Checks Detects dangerous commands + exposed secrets
🚀 Quick Start
Installation
# Clone
git clone https://github.com/Aissamohammedi88/Nexus-id.git
cd Nexus-id

# Install dependencies
pip install pyyaml

# Run
python3 nexus_yaml_verifier.py
