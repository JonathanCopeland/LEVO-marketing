# VERSO Marketing Site

Jekyll marketing site for VERSO: Reading Library, an iPhone app for tracking books you are reading, saving for later, and finished.

## Local Preview

```sh
bundle install
bundle exec jekyll serve
```

If system Ruby tries to write into `/Library/Ruby/Gems`, install the bundle locally instead:

```sh
bundle config set --local path .bundle/vendor
bundle install
bundle exec jekyll serve
```

## Content

- Main app metadata and feature copy live in `_config.yml`.
- Feature icons use Feather icon names from https://github.com/feathericons/feather.
- Privacy policy and release notes live in `_pages/`.
- App icon, iPhone frame, mask, and screenshot preview live in `assets/`.
- Header background color is configured in `_config.yml`.

Update `screenshot_path`, `device_image`, and `device_mask` in `_config.yml` when final App Store imagery is ready.

## Credits

Built from the Automatic App Landing Page Jekyll theme.
