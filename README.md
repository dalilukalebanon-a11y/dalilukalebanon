# Daliluka HTML patch

This package contains a patched `index.html` based on the latest uploaded HTML.

Main patch goals:
- Service intent matching wins over broad conversational/goodbye matching.
- Main menu number shortcuts are protected when the intro menu is active.
- Unknown sensitive intents no longer default to suicide/Embrace.
- `safety_overrides.json` can map `intent_id` to `override_type`.
- Child age detection no longer replaces the request with child protection.
- Known category with no services uses a warm category-specific message.

Upload `index.html` to the root of the GitHub repository. Keep `.nojekyll` in the root.
