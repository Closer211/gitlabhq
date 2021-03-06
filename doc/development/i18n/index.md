# Translate GitLab to your language

The text in GitLab's user interface is in American English by default.
Each string can be translated to other languages.
As each string is translated, it is added to the languages translation file,
and will be available in future releases of GitLab.

Contributions to translations are always needed.
Many strings are not yet available for translation because they have not been externalized.
Helping externalize strings benefits all languages.
Some translations are incomplete or inconsistent.
Translating strings will help complete and improve each language.

## How to contribute

There are many ways you can contribute in translating GitLab.

### Externalize strings

Before a string can be translated, it must be externalized.
This is the process where English strings in the GitLab source code are wrapped in a function that
retrieves the translated string for the user's language.

As new features are added and existing features are updated, the surrounding strings are being
externalized, however, there are many parts of GitLab that still need more work to externalize all
strings.

See [Externalization for GitLab](externalization.md).

### Translate strings

The translation process is managed at [translate.gitlab.com](https://translate.gitlab.com)
using [Crowdin](https://crowdin.com/).
You will need to create an account before you can submit translations.
Once you are signed in, select the language you wish to contribute translations to.

Voting for translations is also valuable, helping to confirm good and flag inaccurate translations.

See [Translation guidelines](translation.md).

### Proof reading

Proof reading helps ensure the accuracy and consistency of translations.
All translations are proof read before being accepted.
If a translations requires changes, you will be notified with a comment explaining why.

Community assistance proof reading translations is encouraged and appreciated.
Requests to become a proof reader will be considered on the merits of previous translations.

- Bulgarian
- Chinese Simplified
  - [Huang Tao](https://crowdin.com/profile/htve)
- Chinese Traditional
  - [Huang Tao](https://crowdin.com/profile/htve)
- Chinese Traditional, Hong Kong
  - [Huang Tao](https://crowdin.com/profile/htve)
- Dutch
- Esperanto
- French
- German
- Italian
- Japanese
- Korean
  - [Huang Tao](https://crowdin.com/profile/htve)
- Portuguese, Brazilian
- Russian
  - [Alexy Lustin](https://crowdin.com/profile/lustin)
  - [Nikita Grylov](https://crowdin.com/profile/nixel2007)
- Spanish
- Ukrainian

If you would like to be added as a proof reader, please [open an issue](https://gitlab.com/gitlab-org/gitlab-ce/issues).

## Release

Translations are typically included in the next major or minor release.
