# Auto Claude

**Autonomous multi-agent coding framework that plans, builds, and validates software for you.**

![Auto Claude Kanban Board](.github/assets/Auto-Claude-Kanban.png)

[![License](https://img.shields.io/badge/license-AGPL--3.0-green?style=flat-square)](./agpl-3.0.txt)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/KCXaPBr4Dj)
[![YouTube](https://img.shields.io/badge/YouTube-Subscribe-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@AndreMikalsen)
[![CI](https://img.shields.io/github/actions/workflow/status/AndyMik90/Auto-Claude/ci.yml?branch=main&style=flat-square&label=CI)](https://github.com/AndyMik90/Auto-Claude/actions)

---

## Download

### Stable Release

<!-- STABLE_VERSION_BADGE -->
[![Stable](https://img.shields.io/badge/stable-2.7.4-blue?style=flat-square)](https://github.com/AndyMik90/Auto-Claude/releases/tag/v2.7.4)
<!-- STABLE_VERSION_BADGE_END -->

<!-- STABLE_DOWNLOADS -->
| Platform | Download |
|----------|----------|
| **Windows** | [Auto-Claude-2.7.4-win32-x64.exe](https://github.com/AndyMik90/Auto-Claude/releases/download/v2.7.4/Auto-Claude-2.7.4-win32-x64.exe) |
| **macOS (Apple Silicon)** | [Auto-Claude-2.7.4-darwin-arm64.dmg](https://github.com/AndyMik90/Auto-Claude/releases/download/v2.7.4/Auto-Claude-2.7.4-darwin-arm64.dmg) |
| **macOS (Intel)** | [Auto-Claude-2.7.4-darwin-x64.dmg](https://github.com/AndyMik90/Auto-Claude/releases/download/v2.7.4/Auto-Claude-2.7.4-darwin-x64.dmg) |
| **Linux** | [Auto-Claude-2.7.4-linux-x86_64.AppImage](https://github.com/AndyMik90/Auto-Claude/releases/download/v2.7.4/Auto-Claude-2.7.4-linux-x86_64.AppImage) |
| **Linux (Debian)** | [Auto-Claude-2.7.4-linux-amd64.deb](https://github.com/AndyMik90/Auto-Claude/releases/download/v2.7.4/Auto-Claude-2.7.4-linux-amd64.deb) |
| **Linux (Flatpak)** | [Auto-Claude-2.7.4-linux-x86_64.flatpak](https://github.com/AndyMik90/Auto-Claude/releases/download/v2.7.4/Auto-Claude-2.7.4-linux-x86_64.flatpak) |
<!-- STABLE_DOWNLOADS_END -->

### Beta Release

> ⚠️ Beta releases may contain bugs and breaking changes. [View all releases](https://github.com/AndyMik90/Auto-Claude/releases)

<!-- BETA_VERSION_BADGE -->
[![Beta](https://img.shields.io/badge/beta-2.7.2--beta.10-orange?style=flat-square)](https://github.com/AndyMik90/Auto-Claude/releases/tag/v2.7.2-beta.10)
<!-- BETA_VERSION_BADGE_END -->

<!-- BETA_DOWNLOADS -->
| Platform | Download |
|----------|----------|
| **Windows** | [Auto-Claude-2.7.2-beta.10-win32-x64.exe](https://github.com/AndyMik90/Auto-Claude/releases/download/v2.7.2-beta.10/Auto-Claude-2.7.2-beta.10-win32-x64.exe) |
| **macOS (Apple Silicon)** | [Auto-Claude-2.7.2-beta.10-darwin-arm64.dmg](https://github.com/AndyMik90/Auto-Claude/releases/download/v2.7.2-beta.10/Auto-Claude-2.7.2-beta.10-darwin-arm64.dmg) |
| **macOS (Intel)** | [Auto-Claude-2.7.2-beta.10-darwin-x64.dmg](https://github.com/AndyMik90/Auto-Claude/releases/download/v2.7.2-beta.10/Auto-Claude-2.7.2-beta.10-darwin-x64.dmg) |
| **Linux** | [Auto-Claude-2.7.2-beta.10-linux-x86_64.AppImage](https://github.com/AndyMik90/Auto-Claude/releases/download/v2.7.2-beta.10/Auto-Claude-2.7.2-beta.10-linux-x86_64.AppImage) |
| **Linux (Debian)** | [Auto-Claude-2.7.2-beta.10-linux-amd64.deb](https://github.com/AndyMik90/Auto-Claude/releases/download/v2.7.2-beta.10/Auto-Claude-2.7.2-beta.10-linux-amd64.deb) |
| **Linux (Flatpak)** | [Auto-Claude-2.7.2-beta.10-linux-x86_64.flatpak](https://github.com/AndyMik90/Auto-Claude/releases/download/v2.7.2-beta.10/Auto-Claude-2.7.2-beta.10-linux-x86_64.flatpak) |
<!-- BETA_DOWNLOADS_END -->

> All releases include SHA256 checksums and VirusTotal scan results for security verification.

---

## Requirements

- **Claude Pro/Max subscription** - [Get one here](https://claude.ai/upgrade)
- **Claude Code CLI** - `npm install -g @anthropic-ai/claude-code`
- **Git repository** - Your project must be initialized as a git repo

---

## Quick Start

1. **Download and install** the app for your platform
2. **Open your project** - Select a git repository folder
3. **Connect Claude** - The app will guide you through OAuth setup
4. **Create a task** - Describe what you want to build
5. **Watch it work** - Agents plan, code, and validate autonomously

---

## Features

| Feature | Description |
|---------|-------------|
| **Autonomous Tasks** | Describe your goal; agents handle planning, implementation, and validation |
| **Parallel Execution** | Run multiple builds simultaneously with up to 12 agent terminals |
| **Isolated Workspaces** | All changes happen in git worktrees - your main branch stays safe |
| **Self-Validating QA** | Built-in quality assurance loop catches issues before you review |
| **AI-Powered Merge** | Automatic conflict resolution when integrating back to main |
| **Memory Layer** | Agents retain insights across sessions for smarter builds |
| **GitHub/GitLab Integration** | Import issues, investigate with AI, create merge requests |
| **Linear Integration** | Sync tasks with Linear for team progress tracking |
| **Cross-Platform** | Native desktop apps for Windows, macOS, and Linux |
| **Auto-Updates** | App updates automatically when new versions are released |

---

## Interface

### Kanban Board
Visual task management from planning through completion. Create tasks and monitor agent progress in real-time.

### Agent Terminals
AI-powered terminals with one-click task context injection. Spawn multiple agents for parallel work.

![Agent Terminals](.github/assets/Auto-Claude-Agents-terminals.png)

### Roadmap
AI-assisted feature planning with competitor analysis and audience targeting.

![Roadmap](.github/assets/Auto-Claude-roadmap.png)

### Additional Features
- **Insights** - Chat interface for exploring your codebase
- **Ideation** - Discover improvements, performance issues, and vulnerabilities
- **Changelog** - Generate release notes from completed tasks

---

## Project Structure

```
Auto-Claude/
├── apps/
│   ├── backend/     # Python agents, specs, QA pipeline
│   └── frontend/    # Electron desktop application
├── guides/          # Additional documentation
├── tests/           # Test suite
└── scripts/         # Build utilities
```

---

## CLI Usage

For headless operation, CI/CD integration, or terminal-only workflows:

```bash
cd apps/backend

# Create a spec interactively
python spec_runner.py --interactive

# Run autonomous build
python run.py --spec 001

# Review and merge
python run.py --spec 001 --review
python run.py --spec 001 --merge
```

See [guides/CLI-USAGE.md](guides/CLI-USAGE.md) for complete CLI documentation.

---

## Korean Fork Modifications (Auto-Claude_ko)

This fork adds dynamic language support for AI agent responses with enhanced security. Changes are designed for extensibility and community contributions.

### Modified Files

#### **Backend - Language Support**

**`apps/backend/prompts_pkg/prompt_generator.py`**
- **Purpose**: Core language instruction generation with dynamic detection
- **Changes**:
  - Added `get_supported_languages()` - Scans `i18n/locales/` folder to auto-detect available languages
  - Added `get_user_language_instruction()` - Generates language-specific instructions for AI prompts
  - Implements prompt injection prevention with sanitization (removes special characters, enforces 50-char limit)
  - Supports CJK languages (Korean, Japanese, Chinese) via Unicode regex
- **How it works**: Reads `AUTO_CLAUDE_USER_LANGUAGE` and `AUTO_CLAUDE_USER_LANGUAGE_NAME` environment variables from frontend, validates against detected languages, sanitizes input, and prepends language instruction to agent prompts

**`apps/backend/prompts_pkg/prompts.py`**
- **Purpose**: Inject language instructions into QA agent prompts
- **Changes**:
  - Imports `get_user_language_instruction()` from prompt_generator
  - Prepends language instruction to `get_qa_reviewer_prompt()` - QA Reviewer sees user's preferred language
  - Prepends language instruction to `get_qa_fixer_prompt()` - QA Fixer responds in user's language
- **How it works**: When QA agents run, they receive localized prompts if user has set a non-English language preference

**`apps/backend/spec/pipeline/agent_runner.py`**
- **Purpose**: Apply language preference to Spec creation agents
- **Changes**:
  - Imports `get_user_language_instruction()` from prompt_generator
  - Adds language instruction at the top of agent prompts in `run()` method
  - Logs language instruction length for debugging
- **How it works**: Spec agents (Gatherer, Writer, Critic, etc.) receive language instructions and generate specifications in user's preferred language

**`apps/backend/runners/roadmap/executor.py`**
- **Purpose**: Apply language preference to Roadmap generation agents
- **Changes**:
  - Imports `get_user_language_instruction()` from prompt_generator
  - Adds language instruction at the top of agent prompts in `AgentExecutor.run_agent()` method
  - Logs language instruction length for debugging
- **How it works**: Roadmap agents (Discovery, Features) receive language instructions and generate roadmaps in user's preferred language

**`apps/backend/ideation/generator.py`**
- **Purpose**: Apply language preference to Ideation generation agents
- **Changes**:
  - Imports `get_user_language_instruction()` from prompt_generator
  - Adds language instruction in `IdeationGenerator.run_agent()` method
  - Adds language instruction in `run_recovery_agent()` method for error recovery
- **How it works**: Ideation agents (Code Improvements, UI/UX, Security, etc.) receive language instructions and generate ideas in user's preferred language

#### **Frontend - Language Transmission**

**`apps/frontend/src/main/agent/agent-process.ts`**
- **Purpose**: Pass user's language preference from settings to backend agents
- **Changes**:
  - Imports `AVAILABLE_LANGUAGES` from i18n constants for validation
  - **In `setupProcessEnvironment()` method** (for task execution):
    - Reads `settings.language` from user preferences
    - Validates language against `AVAILABLE_LANGUAGES` list (frontend validation layer)
    - Creates `languageEnv` object with environment variables:
      - `AUTO_CLAUDE_USER_LANGUAGE` - Language code (e.g., "ko", "fr")
      - `AUTO_CLAUDE_USER_LANGUAGE_NAME` - Display name from i18n config (e.g., "한국어", "Français")
    - Adds `languageEnv` to process environment with proper priority (after gitBashEnv, before claudeCliEnv)
    - Includes error handling with try-catch and console logging for debugging
  - **In `getCombinedEnv()` method** (for roadmap/ideation generation):
    - Reads `settings.language` from user preferences
    - Creates `languageEnv` object with same environment variables as above
    - Returns combined environment with language settings included
    - Ensures roadmap and ideation agents receive language preferences
- **How it works**:
  - Task execution uses `spawnProcess()` → `setupProcessEnvironment()` → language settings passed
  - Roadmap/ideation uses `spawnRoadmapProcess()`/`spawnIdeationProcess()` → `getCombinedEnv()` → language settings passed
  - Both paths now support user's language preference, bridging the gap between frontend UI settings and backend AI agents

### Added Files

**`tests/test_language_detection.py`**
- **Purpose**: Comprehensive test suite for language detection and security validation
- **Features**:
  - Tests dynamic language detection from i18n folder
  - Validates English default behavior (no instruction)
  - Verifies French and Korean support (if folders exist)
  - Security tests:
    - Unsupported language rejection
    - Prompt injection prevention (malicious newlines, special characters)
    - Length limit enforcement (50 chars)
- **How to use**: `python tests/test_language_detection.py`
- **Output**: 7 tests covering functionality and security (all pass)

### Key Features

#### **1. Backend Dynamic Language Detection (Security Layer)**
- **Purpose**: Validates user language input against allowed languages to prevent prompt injection attacks
- **How it works**: Backend scans `apps/backend/prompts_pkg/locales/` folder to auto-detect available languages
- **Security validation**: User-provided language code is checked against this whitelist before generating AI prompts
- **Defense in depth**: Even if frontend is bypassed (e.g., CLI usage, environment variable manipulation), backend rejects unauthorized languages

#### **2. Security (Prompt Injection Prevention)**
- **Allowlist validation**: Only languages with locales folders are accepted by backend
- **Character sanitization**: Removes dangerous characters (newlines, control chars, markdown injection)
- **Length limit**: Language names capped at 50 characters
- **Multiple validation layers**:
  - **Frontend**: Validates against `AVAILABLE_LANGUAGES` in `constants/i18n.ts` when user selects language in UI
  - **Backend**: Validates against `get_supported_languages()` when generating AI prompts
- **Why both layers?**: Frontend can be bypassed (CLI, direct API calls), so backend provides final security enforcement

#### **3. Extensibility**

**To add a new language (requires 3 steps):**

**Step 1: Create translation files**
```bash
mkdir -p apps/frontend/src/shared/i18n/locales/ja
# Add translation JSON files: common.json, settings.json, etc.
```

**Step 2: Register in frontend constants**
Edit `apps/frontend/src/shared/constants/i18n.ts`:
```typescript
export type SupportedLanguage = 'en' | 'fr' | 'ko' | 'ja';  // Add 'ja'

export const AVAILABLE_LANGUAGES = [
  { value: 'en' as const, label: 'English', nativeLabel: 'English' },
  { value: 'fr' as const, label: 'French', nativeLabel: 'Français' },
  { value: 'ko' as const, label: 'Korean', nativeLabel: '한국어' },
  { value: 'ja' as const, label: 'Japanese', nativeLabel: '日本語' }  // Add this
] as const;
```

**Step 3: Register in i18next resources**
Edit `apps/frontend/src/shared/i18n/index.ts`:
```typescript
// Add imports
import jaCommon from './locales/ja/common.json';
import jaSettings from './locales/ja/settings.json';
// ... (import all 11 translation files)

export const resources = {
  en: { /* ... */ },
  fr: { /* ... */ },
  ko: { /* ... */ },
  ja: {  // Add this
    common: jaCommon,
    settings: jaSettings,
    // ... (add all namespaces)
  }
} as const;
```

**Backend auto-detection (no changes needed):**
- `prompt_generator.py` - Auto-scans folder (security validation only)
- `prompts.py` - Uses dynamic function (no hardcoding)
- `agent_runner.py` - Uses dynamic function (no hardcoding)

#### **4. Supported Languages (Current)**
- **English** (en) - Default, no instruction needed
- **French** (fr) - Full support with accent characters
- **Korean** (ko) - CJK support *(requires locales/ko/ folder)*
- **Japanese** (ja) - CJK support *(requires locales/ja/ folder)*
- **Chinese** (zh) - CJK support *(requires locales/zh/ folder)*

### Testing

Run the test suite to verify:
```bash
python tests/test_language_detection.py
```

Expected output:
```
[PASS] Detected languages: ['en', 'fr']
[PASS] English returns empty string (correct)
[PASS] French language instruction generated
[PASS] Malicious newlines removed
[PASS] Prompt injection sanitized
[PASS] Length limited to 50 chars
[PASS] All tests completed!
```

### Troubleshooting

#### **Language patch not working (still getting English responses)**

**Symptom**: You've installed Auto-Claude_ko but AI responses are still in English even though Korean is selected in settings.

**Cause**: If you previously had Auto-Claude installed in a different location, your `autoBuildPath` setting may point to the old (unpatched) installation.

**How Auto-Claude works**:
- Settings are stored in `~/AppData/Roaming/auto-claude/settings.json` (Windows) or `~/.config/auto-claude/settings.json` (macOS/Linux)
- `autoBuildPath` tells the app where to find the backend Python code
- When set to an old installation, the app uses that folder's code instead of the current Git repo

**Solution**:
1. Open Settings → General
2. Check the "Auto-Build Source Path" setting
3. If it points to an old Auto-Claude folder:
   - Click "Browse" and select the current `Auto-Claude_ko/apps/backend` folder
   - Or delete the old folder entirely and reinstall
4. Restart the app for changes to take effect

**Verification**:
- After changing paths, run a roadmap or ideation task
- AI responses should now appear in Korean
- If still in English, check the Settings path again and ensure you're using the Auto-Claude_ko repository

### Design Philosophy

**Convention over Configuration**: Following industry standards (i18next, Django, VS Code), language support is driven by folder structure rather than configuration files. This reduces maintenance burden and enables non-developers to contribute translations.

**Security by Default**: All user input (language names) is sanitized before injection into AI prompts. Multiple validation layers ensure malicious input cannot compromise agent behavior.

---

## Development

Want to build from source or contribute? See [CONTRIBUTING.md](CONTRIBUTING.md) for complete development setup instructions.

For Linux-specific builds (Flatpak, AppImage), see [guides/linux.md](guides/linux.md).

---

## Security

Auto Claude uses a three-layer security model:

1. **OS Sandbox** - Bash commands run in isolation
2. **Filesystem Restrictions** - Operations limited to project directory
3. **Dynamic Command Allowlist** - Only approved commands based on detected project stack

All releases are:
- Scanned with VirusTotal before publishing
- Include SHA256 checksums for verification
- Code-signed where applicable (macOS)

---

## Available Scripts

| Command | Description |
|---------|-------------|
| `npm run install:all` | Install backend and frontend dependencies |
| `npm start` | Build and run the desktop app |
| `npm run dev` | Run in development mode with hot reload |
| `npm run package` | Package for current platform |
| `npm run package:mac` | Package for macOS |
| `npm run package:win` | Package for Windows |
| `npm run package:linux` | Package for Linux |
| `npm run package:flatpak` | Package as Flatpak (see [guides/linux.md](guides/linux.md)) |
| `npm run lint` | Run linter |
| `npm test` | Run frontend tests |
| `npm run test:backend` | Run backend tests |

---

## Contributing

We welcome contributions! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for:
- Development setup instructions
- Code style guidelines
- Testing requirements
- Pull request process

---

## Community

- **Discord** - [Join our community](https://discord.gg/KCXaPBr4Dj)
- **Issues** - [Report bugs or request features](https://github.com/AndyMik90/Auto-Claude/issues)
- **Discussions** - [Ask questions](https://github.com/AndyMik90/Auto-Claude/discussions)

---

## License

**AGPL-3.0** - GNU Affero General Public License v3.0

Auto Claude is free to use. If you modify and distribute it, or run it as a service, your code must also be open source under AGPL-3.0.

Commercial licensing available for closed-source use cases.

---

## Star History

[![GitHub Repo stars](https://img.shields.io/github/stars/AndyMik90/Auto-Claude?style=social)](https://github.com/AndyMik90/Auto-Claude/stargazers)

[![Star History Chart](https://api.star-history.com/svg?repos=AndyMik90/Auto-Claude&type=Date)](https://star-history.com/#AndyMik90/Auto-Claude&Date)
