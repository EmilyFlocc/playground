To reproduce, also clone https://github.com/EmilyFlocc/my-module and yarn link the two (to resolve the need for gitkeys etc)

Run playground in dev mode, and the list appears as expected.

Run yarn generate and yarn preview, and the list does not appear within the for loop.

Package structure follows https://nuxtjs.org/docs/configuration-glossary/configuration-components/#library-authors