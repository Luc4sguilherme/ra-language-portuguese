# Brazilian Portuguese Messages for React-Admin

Brazilian Portuguese messages for [react-admin](https://github.com/marmelab/react-admin), the frontend framework for building admin applications on top of REST/GraphQL services.

[![react-admin-demo](https://marmelab.com/react-admin/img/react-admin-demo-still.png)](https://vimeo.com/268958716)

## Installation

```sh
npm install --save ra-language-portuguese
```

or

```sh
yarn add @luc4sguilherme/ra-language-portuguese
```

## Usage

```js
import ptBrMessages from '@luc4sguilherme/ra-language-portuguese';
import polyglotI18nProvider from 'ra-i18n-polyglot';

const messages = {
  'pt-br': ptBrMessages,
};
const i18nProvider = polyglotI18nProvider(locale => messages[locale], 'pt-br');

<Admin i18nProvider={i18nProvider}>
  ...
</Admin>
```

## License

This translation is licensed under the MIT License.
