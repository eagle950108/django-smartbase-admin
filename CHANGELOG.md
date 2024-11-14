# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### 0.0.2 (2024-11-14)


### Features

* #BOOK-1998 advanced filtering implementation ([#16](http://redmine.smartbase.sk/issues/16)) ([39cb9ee](https://github.com/dev/django_smartshop/commit/39cb9ee4d3bd48799f85db6027574f007ad5b815)), closes [#BOOK-1998](http://redmine.smartbase.sk/issues/BOOK-1998) [#BOOK-1998](http://redmine.smartbase.sk/issues/BOOK-1998) [#BOOK-1998](http://redmine.smartbase.sk/issues/BOOK-1998) [#BOOK-1998](http://redmine.smartbase.sk/issues/BOOK-1998) [#BOOK-1998](http://redmine.smartbase.sk/issues/BOOK-1998)
* #BOOK-2024 date operator before and after ([2dde3a1](https://github.com/dev/django_smartshop/commit/2dde3a1eba5dc00a036034968a3bd0a0fe18ca0e)), closes [#BOOK-2024](http://redmine.smartbase.sk/issues/BOOK-2024)
* add optional ordering to SBAdminInline ([db8262b](https://github.com/dev/django_smartshop/commit/db8262b7398051ebeaa19fef4016f4c626c88431))
* add reference to request to multiple SBAdmin methods ([#25](http://redmine.smartbase.sk/issues/25)) ([6a334c2](https://github.com/dev/django_smartshop/commit/6a334c2cbd698ca6edfce607c942967267156e9c))
* added option to define color of badges when array formatter is used ([#24](http://redmine.smartbase.sk/issues/24)) ([5f18ec4](https://github.com/dev/django_smartshop/commit/5f18ec49bf4698595b2de9e6ac07c04b477289e3))
* added option to override certain classes via SB_ADMIN_DEPENDENCY_INJECTION setting ([217a1ca](https://github.com/dev/django_smartshop/commit/217a1cac2d4b6c9bf32c44e6beda74c64c0da0b3))
* added option to override certain classes via SB_ADMIN_DEPENDENCY_INJECTION setting ([b531bc5](https://github.com/dev/django_smartshop/commit/b531bc5cae8d666a180cb92285762a89f204429d))
* added option to use action when POST method is used ([46eeaee](https://github.com/dev/django_smartshop/commit/46eeaeed4cbd2069c43f4d6db01dc686d000e938))
* **detail:** added previous, next url context, disabled JS search in autocomplete ([d28ce95](https://github.com/dev/django_smartshop/commit/d28ce95af5d3a7b43b0e386cd5aa5c5d5ba43075))
* **detail:** prev next and count in detail ([d5f83cf](https://github.com/dev/django_smartshop/commit/d5f83cf7a129e72c746ce26397f7fff86944ea42))
* expand XLSXFieldOptions, add new formatters and expand xlsx export ([#10](http://redmine.smartbase.sk/issues/10)) ([3056d8e](https://github.com/dev/django_smartshop/commit/3056d8e30db855244c91505d4bfab3a582be4734))
* FromValuesAutocompleteWidget with ability to retrieve unique values for column ([f075dfd](https://github.com/dev/django_smartshop/commit/f075dfda1a85f50d167767e94a62ab9252b57be0))
* FromValuesAutocompleteWidget with ability to retrieve unique values for column ([d7b92f3](https://github.com/dev/django_smartshop/commit/d7b92f3cb2b3b72cddd285b70e884833f4f6980f))
* hide ordering data in table inline if change perm is False, reworked readonly fields ([#26](http://redmine.smartbase.sk/issues/26)) ([a114bbd](https://github.com/dev/django_smartshop/commit/a114bbd78f9f714ae44f26222c2b5048c1d195fe))
* **list:** added option to group list actions ([bf46699](https://github.com/dev/django_smartshop/commit/bf466994adee050b82114f38b38149b4a765fc8f))
* multiselect checkbox filter and form widget for simple options ([#3](http://redmine.smartbase.sk/issues/3)) ([46542d2](https://github.com/dev/django_smartshop/commit/46542d23e198a527baeaafe501d63ff10aa230c0))
* new type of visual for tabulator header filters ([#13](http://redmine.smartbase.sk/issues/13)) ([ced6035](https://github.com/dev/django_smartshop/commit/ced6035670b5b2cc71217634271386f59f8cb12c))
* **tabulator:** allow POST method for tabulator data fetch ([b5cfd08](https://github.com/dev/django_smartshop/commit/b5cfd080ed690b04f6df2313ac948da68887d1b6))


### Bug Fixes

* [#22512](http://redmine.smartbase.sk/issues/22512) fixed ordering by annotated field when `sbadmin_previous_next_buttons_enabled` or when ordering field is not visible ([#18](http://redmine.smartbase.sk/issues/18)) ([bdbcfa5](https://github.com/dev/django_smartshop/commit/bdbcfa5d6bf83fec873866381e7438c33120436a))
* #BOOK-2022 ([b42afcb](https://github.com/dev/django_smartshop/commit/b42afcbe0edb56f890cf44bec5025a8922df6ebc)), closes [#BOOK-2022](http://redmine.smartbase.sk/issues/BOOK-2022)
* check for existence of sec_fetch_site metadata ([#20](http://redmine.smartbase.sk/issues/20)) ([6a003b9](https://github.com/dev/django_smartshop/commit/6a003b9270a33baef10a5fc8851bc87df5085323))
* ckeditor widget template name ([4e5d853](https://github.com/dev/django_smartshop/commit/4e5d853f44a6732bf2405b0464014d53f05f43f5))
* encode URL params for filter, node.js build setup ([7052e01](https://github.com/dev/django_smartshop/commit/7052e0130fadc8c55fb2460848e704c80390041d))
* fixed actions form registration ([#23](http://redmine.smartbase.sk/issues/23)) ([214ed89](https://github.com/dev/django_smartshop/commit/214ed89a46ee259c27316b64dc306a45f9035da0))
* fixed ckeditor uploading field ([7a1ee73](https://github.com/dev/django_smartshop/commit/7a1ee73dacd4e89b15118c86ab2c5024a855a3ee))
* fixed dashboard error when get_search_fields not presented ([529cb2e](https://github.com/dev/django_smartshop/commit/529cb2ea9c4742c6c945511a644e36553e4820e2))
* fixed enter in filter field and missing quick search ([9239ad7](https://github.com/dev/django_smartshop/commit/9239ad78a65f5263ee14babbeb869f110135c01c))
* fixed init of non sb widgets ([b28529d](https://github.com/dev/django_smartshop/commit/b28529d4010815b69e0807cc6e782766e548c441))
* fixed list action to work also on non table list views ([4a12212](https://github.com/dev/django_smartshop/commit/4a12212cc4701a33298faa0dc00befbdfa00cf77))
* fixed missing static in template and removed unused css ([#8](http://redmine.smartbase.sk/issues/8)) ([526ee05](https://github.com/dev/django_smartshop/commit/526ee058f3537debd4036b973683d06239ded74a))
* fixed radio choice field label ([c8db3a3](https://github.com/dev/django_smartshop/commit/c8db3a3afe6acab647e0e41fa90227950c15664c))
* fixed saved views when POST is used ([4e66964](https://github.com/dev/django_smartshop/commit/4e669649cfe519667493bd6d1e252abcdae57ebe))
* fixed shortcuts retrieval ([5170ed6](https://github.com/dev/django_smartshop/commit/5170ed6b58c4f50ebcf9fa0c01e6f1a7edf0e6cb))
* fixed sorting when POST method is used ([a3a3982](https://github.com/dev/django_smartshop/commit/a3a3982cd0fb7e3a2e826d7639ed881c149af6f6))
* fixed width of columns when new data arrives ([03fea1b](https://github.com/dev/django_smartshop/commit/03fea1b1584ac90899b7e6f5c756823dbbb89674))
* fixed wrong functionality of remove button in filter ([0e96b27](https://github.com/dev/django_smartshop/commit/0e96b27729644751998f0c9c99a388cc3535a794))
* fixed wrong order of annotates resulting in bad query ([4bb13c4](https://github.com/dev/django_smartshop/commit/4bb13c4bce44d7dc8442c2c844769adbc3f73af3))
* fixes double submit on enter pressed when filtering ([e80985e](https://github.com/dev/django_smartshop/commit/e80985ed81b1c18a90ecb130bda342e7201fb439))
* fixes saved table views with special characters in name ([dca2d0b](https://github.com/dev/django_smartshop/commit/dca2d0b7c958463d302797cf210061d425d8154b))
* include dist folder in result wheel ([#9](http://redmine.smartbase.sk/issues/9)) ([464671c](https://github.com/dev/django_smartshop/commit/464671cff61e587a27db86f4bb7e279a406f5e62))
* incorrect loading of get values in case of bulk delete, fake inline verbose name ([6ccb11d](https://github.com/dev/django_smartshop/commit/6ccb11d4cc38d54f647c146f730cb3b93c6df344))
* **list:** added additional header to distinguish tabulator calls ([affcdd1](https://github.com/dev/django_smartshop/commit/affcdd1b378915b0c4bbe10748a87183a952d099))
* logout form ([#15](http://redmine.smartbase.sk/issues/15)) ([44124f5](https://github.com/dev/django_smartshop/commit/44124f592d2335017f4f3f3ce3c100d399fe5fff))
* modal attrs missing space ([904ea8f](https://github.com/dev/django_smartshop/commit/904ea8f01ce640784a6a6a35ce88c093fec03d28))
* modal view initialisation of autocomplete widget ([8a626f6](https://github.com/dev/django_smartshop/commit/8a626f6fdd14cdc371cfe9614d2a2fde07ebb64e))
* parent instance inline permissions ([3198851](https://github.com/dev/django_smartshop/commit/3198851135b6a93ee762bae44078429434d7f585))
* pass ckeditor config_name into widget ([9b2bf79](https://github.com/dev/django_smartshop/commit/9b2bf797c62170ec44f70410109224a7f64bee57))
* send extra_context correctly ([e25c672](https://github.com/dev/django_smartshop/commit/e25c6721fa01125dcdc00fdaa5314f27fdb0faaa))
* show selected option instead of daterange for in_the_last and in_the_next ([188d661](https://github.com/dev/django_smartshop/commit/188d661d7df9c790d9e0132e560a59a61c2b4cef))
* svg display in clearable_file_input ([53c622b](https://github.com/dev/django_smartshop/commit/53c622be60ccac61bc27b4ef17ea4a194c4a3f07))
* **widget:** datepicker initialisation fix ([5f6ef05](https://github.com/dev/django_smartshop/commit/5f6ef0500f359a11633017625ee7b9c570e8a427))
