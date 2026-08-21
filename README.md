# new-hire-orientation-checklist

Coordinates pre-start, day-one, first-week, and follow-up obligations with owners and evidence.

It produces:

- **New Hire Orientation Checklist:** a working artifact built from supplied facts, labeled inference, and visible missing fields.

It executes the [New Hire Orientation Checklist playbook](https://www.andrewluxem.com/playbooks/new-hire-orientation-checklist). The playbook teaches the framework. This skill runs it and returns a working artifact.

**Static by construction: no dependencies, executable code, telemetry, network calls, remote instructions, auto-update, scheduled work, or background behavior.** It reads only the files in its own skill folder. Nothing happens until a user or agent invokes it.

## Install

Clone and copy the skill into Claude Code:

```bash
git clone https://github.com/andrewluxem/new-hire-orientation-checklist.git
cp -r new-hire-orientation-checklist/skills/new-hire-orientation-checklist ~/.claude/skills/
```

For Codex, copy the same complete folder to the Codex skills directory:

```bash
cp -r new-hire-orientation-checklist/skills/new-hire-orientation-checklist ~/.codex/skills/
```

Or install it as a Claude Code plugin:

```text
/plugin marketplace add andrewluxem/new-hire-orientation-checklist
/plugin install new-hire-orientation-checklist@new-hire-orientation-checklist
```

For clients that install from an archive, use the versioned [new-hire-orientation-checklist v1.0.0 ZIP](https://www.andrewluxem.com/downloads/new-hire-orientation-checklist-v1.0.0.zip).

## Invoke it

```text
Build the new hire orientation checklist
Use the new-hire-orientation-checklist skill.
```

Naming the skill is always valid: `use the new-hire-orientation-checklist skill`.

## Files

```text
.claude-plugin/
  plugin.json
  marketplace.json
skills/new-hire-orientation-checklist/
  assets/new-hire-orientation-checklist-template.md
  LICENSE.md
  meta.yaml
  references/orientation-checklist-standard.md
  SKILL.md
README.md
LICENSE
```

The complete canonical package is copied under `skills/new-hire-orientation-checklist/`, including every asset, reference, test prompt, source note, changelog entry, and license file present in the source.

## Versioning

Plugin installation is version-pinned. When behavior changes, update the version consistently in `SKILL.md`, `meta.yaml`, `.claude-plugin/plugin.json`, and `.claude-plugin/marketplace.json`, then add a changelog entry. Reinstalling is an explicit update; this repository never auto-updates itself.

## License

MIT. See [LICENSE](LICENSE). The canonical skill folder carries the same authorization in [skills/new-hire-orientation-checklist/LICENSE.md](skills/new-hire-orientation-checklist/LICENSE.md).

---

## More playbooks

This skill packages one playbook from the free library at [github.com/andrewluxem/playbooks](https://github.com/andrewluxem/playbooks). Every playbook is free to read, with no email required.
