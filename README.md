# Capitally Assets

This repository is a central hub for storing and collaborating on various assets used in Capitally.

## Contents

- **app/importTemplates**: [Import Templates](https://www.mycapitally.com/help/import-from-a-broker) for various brokers
- **app/taxPresets**: [Tax presets](https://www.mycapitally.com/help/tax-presets) for countries
- **app/taxProgramSnippets**: reusable snippets to be used in Tax Presets
- **static/brokers**: logos of brokers referenced in Import Templates

## Contributing

We welcome contributions from the community! If you have any assets that you believe would be valuable to include in this repository, feel free to do so!

Ensure your contributions follow the repository's structure and naming conventions. For questions or assistance, please open an issue.

### Import Templates

To create a new import template, simply create it in the app and export it.
You can also import any template from this repository into the app, modify it, and then export it back here.

When submitting, please make sure that:

- the template has the `info`, `author`, `group` and `logoURL` fields filled out - you will need
  to edit the file manually for templates created within the app
- in broker templates, the first column should be an `Account` that uses a `$template`,
  please refer to existing templates for reference
- the file name starts with `app-` (for imports from apps) or `broker-` (for imports from brokers or crypto exchanges)
- it's added to one of the `app/importTemplates` subfolders

### Tax Presets

To create a new Tax Preset, simply create it in the app and export it.
You can also import any preset from this repository into the app, modify it, and then export it back here.

When submitting, please make sure that:

- the preset has the `note` field filled out with all information that an end user
  might need to understand the results
- the file name starts with `tax-ISO-`, where ISO is the two-letter ISO symbol od the country
- it's added directly to the `app/taxPresets` folder

## Contact

For questions, suggestions, or feedback regarding Capitally Assets, please contact us at [hello@mycapitally.com](mailto:hello@mycapitally.com).
