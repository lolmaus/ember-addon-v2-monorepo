# my-addon

This monorepo has been created with:

```sh
ember addon my-addon \
  --blueprint @embroider/addon-blueprint \
  --pnpm \
  --addon-location="packages/my-addon" \
  --test-app-name="my-app" \
  --test-app-location="packages/my-app" \
  -dir ember-reproduction-ember-data-issue

cd ember-reproduction-ember-data-issue
pnpm i 
pnpm start
```

It fails to build with:

>   - errorMessage: [NodeWrapper:4 /home/lolmaus/Code/mainmatter/mainmatter/ember-reproduction-ember-data-issue/node_modules/.pnpm/ember-cli-test-loader@3.1.0/node_modules/ember-cli-test-loader/test-support] is not a SourceNode

Full error dump log: https://gist.github.com/lolmaus/bc76bcc9201e2d05a00f479e72c25315#file-error-dump-log

## Compatibility

- Ember.js v4.8 or above
- Embroider or ember-auto-import v2

## Installation

```
ember install my-addon
```

## Usage

[Longer description of how to use the addon in apps.]

## Contributing

See the [Contributing](CONTRIBUTING.md) guide for details.

## License

This project is licensed under the [MIT License](LICENSE.md).
