# Capitally Assets

This repository is a central hub for storing and collaborating on various assets used in Capitally.

## Contents

- **app/importPresets**: [Import Presets](https://www.mycapitally.com/help/import-from-a-broker) for various brokers
- **app/importTemplates**: [legacy Import Templates](https://www.mycapitally.com/help/import-from-a-broker) for various brokers
- **app/taxPresets**: [Tax presets](https://www.mycapitally.com/help/tax-presets) for countries
- **app/importProgramSnippets**: reusable snippets to be used in Import Presets
- **app/taxProgramSnippets**: reusable snippets to be used in Tax Presets
- **static/brokers**: logos of brokers referenced in Import Templates

## Contributing

We welcome contributions from the community! If you have any assets that you believe would be valuable to include in this repository, feel free to do so!

Ensure your contributions follow the repository's structure and naming conventions. For questions or assistance, please open an issue.

### Import Presets

To create a new import presets, simply create it in the app and export it.
You can also import any preset from this repository into the app, modify it, and then export it back here.

When submitting, please make sure that:

- the template has the `info`, `author`, `group` and `icon` fields filled out
- presets for brokers should create an `Account`
- the file name starts with `p-app-` (for imports from apps) or `p-broker-` (for imports from brokers or crypto exchanges)
- it's added to one of the `app/importPresets` subfolders

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
