# ABAP Florilegium
A collection of the most popular ABAP-related repository sorted by category and scope of use.

<a name="up" />

## Categories

- [eMail & Document Processing](#docproc)
- [UI & Presentation](#ui)
- [Code & Data Visualization](#codevis)
- [Code Templates & Generator](#codetemp)
- [Data Formatting](#dataform)
- [Data Processing](#dataproc)
- [Testing](#test)
- [Logging](#log)
- [Packages & Versioning](#git)
- [Code Inspector / Linter / Performance](#sci)
- [Api & Services](#api)
- [Integration](#int)
- [Adt & Eclipse](#adt)
- [Threading](#thr)
- [Generic Utilities](#gen)
- [Samples & Learning](#sam)
- [Documentation & Informations](#doc)

<a name="docproc" />

### 🗒️ eMail & Document Processing	
|   project      |     description      | tags |
|     :---:    |     :---:      | :---: |
|  [abap2xlsx](https://github.com/abap2xlsx/abap2xlsx)   | Generate your professional Excel spreadsheet from ABAP     | `excel`
|  [zcl_docx](https://github.com/AntonSikidin/zcl_docx)   | Best way to create Microsoft Word docx from abap     | `word`
|  [zcl_pdf](https://github.com/beraadim/zcl_pdf)   | A pure stand alone ABAP class for creating PDFs in SAP on any ABAP system | `pdf`
|  [xtt](https://github.com/bizhuka/xtt)   | ABAP template engine for Excel, Word, Html & Pdf | `excel`, `word`, `pdf`
|  [easyHtmlEmail](https://github.com/DryDumbHead/easyHtmlEmail)   | Easy to Generate & Maintain Email in SAP (ABAP + HTML/CSS) | `email`, `html`
|  [text2tab](https://github.com/sbcgua/text2tab)   | TAB-delimited text parser for ABAP | `text`
|  [ABAP2XLSX_HELPER](https://github.com/boy0korea/ABAP2XLSX_HELPER)   | abap2xlsx helper | `excel`
|  [ABAP_Sending_Email](https://github.com/eliramy/ABAP_Sending_Email)   | ABAP Sending Email - Class Encapsulation | `email`
|  [ABAP-HTML-eMail](https://github.com/vidyadharg/ABAP-HTML-eMail)   | SAP ABAP send email using eMail Templates with or without CDS | `email`

<a name="ui" />

### 🎨 UI & Presentation
|   project      |     description      | tags |
|     :---:    |     :---:      | :---: |
|  [abap2UI5](https://github.com/oblomov-dev/abap2UI5) | Development of UI5 Apps in pure ABAP | `sapui5`
|  [falv](https://github.com/fidley/falv) | FALV - Fast ALV Grid | `alv`
|  [eui](https://github.com/bizhuka/eui) | Easy UI in SAP | `alv`, `screens`
|  [sapui5-deployer](https://github.com/Yelcho/sapui5-deployer) | ABAP deployment of SAPUI5 apps from Github | `sapui5`
|  [abap-ui-toolbox](https://github.com/stockbal/abap-ui-toolbox) | Tools for UI Development like Improved ALV Grid and GUI control framework | `alv`, `gui`
|  [mvp-salv-table-container-abap](https://github.com/ivantyumenyev/mvp-salv-table-container-abap) | ALV Grid report based on Model-View-Presenter pattern with dynpro screen and container | `alv`
|  [TALV](https://github.com/AES0P/TALV) | An ALV report framework based on ABAP | `alv`

<a name="codevis" />

### 💻 Code & Data Visualization
|   project      |     description      | tags |
|     :---:    |     :---:      | :---: |
|  [ABAP-Object-Visualizer](https://github.com/larshp/ABAP-Object-Visualizer) | Visualize complex object hierarchies using debugger script | `viewer`
|  [Simple Data Explorer](https://github.com/ysichov/Simple-Data-Explorer) | Simple Data Explorer | `viewer`
|  [abap-markdown](https://github.com/koemaeda/abap-markdown) | ABAP Markdown | `markdown`
|  [ztoad](https://github.com/marianfoo/ztoad) | ABAP Open SQL Editor | `viewer`
|  [abap2yuml](https://github.com/fabiopagoti/abap2yuml) | ABAP Markdown | `uml`
|  [ABAP-to-PlantUML](https://github.com/nomssi/ABAP-to-PlantUML) | Create UML Class and Sequence Diagrams from ABAP Code | `uml`
|  [ZUML_DIAGRAM](https://github.com/coreline/ZUML_DIAGRAM) | The UML Diagram tool for ABAP using PlantUML | `uml`
|  [ABAPplantUML](https://github.com/sdfraga/ABAPplantUML) | plantUML tools for ABAP Dev | `uml`
|  [abap_debugger_data_view_extension](https://github.com/objective-partner/abap_debugger_data_view_extension) | Extensions to abap debugger to be able to view itab and structure data in a abap-coding friendly way | `debugger`
|  [abap-db-browser](https://github.com/stockbal/abap-db-browser) | ABAP DB Browser (Tables, Views, CDS Views, Custom Queries, Joins, ...) | `viewer`
|  [abap_debugger_object_graph_extension](https://github.com/marcellourbani/abap_debugger_object_graph_extension) | ABAP debugger extension to visualize objects as graphs | `debugger`
|  [abap-code-search-tools](https://github.com/stockbal/abap-code-search-tools) | ABAP Code Search | `finder`
|  [ABAP-2-CODE-CHARTA](https://github.com/BenjaminWeisheit/ABAP-2-CODE-CHARTA) | Covert ABAP Metrics to Code Charta | `viewer`
|  [ZDDIC_FINDER](https://github.com/coreline/ZDDIC_FINDER) | ABAP Dictionary object finder tool | `finder`
|  [scf](https://github.com/reyemsaibot/scf) | You are looking for a specific code snippet in your ABAP code. Then use the Source Code Finder to search for every occurrence of it. | `search`
|  [abapTableCompare](https://github.com/cavabap/abapTableCompare) | Compares two tables and reports which lines are unchanged, inserted, deleted or changed. | `diff`
|  [abapMermaid](https://github.com/WegnerDan/abapMermaid) |Integrate Mermaid Diagrams in SAP GUI Containers | `mermaid`
|  [cdsfindanno](https://github.com/attilaberencsi/cdsfindanno) | Find Annotation Samples in CDS Views | `finder`
|  [trlist](https://github.com/attilaberencsi/trlist) | Transport Status List | `transport`
|  [abap-soql-query](https://github.com/gprs555/abap-soql-query) | ABAP Tool for SOQL Query | `soql`
|  [abap_file_browser](https://github.com/alaible/abap_file_browser) | F4 file browser written in abap | `viewer`
|  [envysis](https://github.com/sandraros/envysis) | Environment Analysis for ABAP Workbench Objects (where-used list, etc.) | `finder`
|  [markdown_from_table_or_structure](https://github.com/Keller-Michael/markdown_from_table_or_structure) | 🏭 generate Markdown table from internal table or structure in ABAP | `markdown`
|  [MBT-Transport-Request](https://github.com/Marc-Bernard-Tools/MBT-Transport-Request) | The ultimate enhancement for displaying of transport requests in SAP GUI | `transport`
|  [ZEX_HTML_EDITOR](https://github.com/abeljohny/ZEX_HTML_EDITOR) | A simple HTML Editor and Browser written in ABAP | `html`

<a name="codetemp" />

### 💡 Code Templates and Generator
|   project      |     description      | tags |
|     :---:    |     :---:      | :---: |
|  [abap-ddic-creator](https://github.com/Leo-SDU/abap-ddic-creator) | create table and data elements and domains by batching | `object generation`
|  [AbapGenerator](https://github.com/OberstVonGatow/AbapGenerator) | Generate ABAP Objects from Templates | `template`
|  [abap_mustache](https://github.com/sbcgua/abap_mustache) | Mustache template engine for ABAP | `mustache`
|  [FORMfactor](https://github.com/larshp/FORMfactor) | ABAP - Refactor FORMs to local classes | `refactoring`
|  [abap_bapi_bo_class_generator](https://github.com/alwinvandeput/abap_bapi_bo_class_generator) | ABAP BAPI Business Object Class Generator | `object generation`
|  [guidrasil](https://github.com/tricktresor/guidrasil) | ABAP GUI designer for Prototyping and more | `gui`
|  [abap_gui_boilerplate](https://github.com/sbcgua/abap_gui_boilerplate) | Boilerplate for ABAP simple application with HTML GUI screen | `gui`
|  [selection-criteria-as-class](https://github.com/Keller-Michael/selection-criteria-as-class) |  handle selection criteria as global class to keep all criteria together | `screen`
|  [abap-tvarvc](https://github.com/raketenstart-abap/abap-tvarvc) | TVARVC Helper | `tvarvc`
|  [abap_include_assembler](https://github.com/sbcgua/abap_include_assembler) | A tool to statically include includes into the main program | `include`
|  [zeegor](https://github.com/vidyadharg/zeegor) | Simple Batch Programming in ABAP call transaction and Batch session(SM35). | `batch`
|  [AbapOOReports](https://github.com/oxgl/AbapOOReports) | ABAP Object Oriented Reporting | `oop`
|  [ABAP-GlobalToLocal](https://github.com/SAP2Moose/ABAP-GlobalToLocal) | APack global ABAP classes in a single report - Simplifies distribution of complex codings | `pack`

<a name="dataform" />

### 📔 Data Formatting
|   project      |     description      | tags |
|     :---:    |     :---:      | :---: |
|  [abap_fm_json](https://github.com/cesar-sap/abap_fm_json) | JSON adapter for ABAP Function Modules | `json`
|  [JSON2ABAPType](https://github.com/fidley/JSON2ABAPType) | Creator of ABAP types on a base of JSON structure | `json`
|  [abap-file-formats](https://github.com/SAP/abap-file-formats) | File formats that define and specify the file representation for ABAP development objects | `json`
|  [ajson](https://github.com/sbcgua/ajson) | Yet another json parser serializer for ABAP | `json`
|  [zcl_mdp_json](https://github.com/fatihpense/zcl_mdp_json) | MDP ABAP JSON library that can generate and parse any JSON string | `json`
|  [CommonRegexABAP](https://github.com/dmitry-zharinov/CommonRegexABAP) | CommonRegex port for ABAP | `regex`
|  [abap-json-serialization](https://github.com/timostark/abap-json-serialization) | Fastest possible JSON serialization | `json`
|  [abap-json-encoder-decoder](https://github.com/valdirmendesdev/abap-json-encoder-decoder) | One more JSON Encoder/Decoder in ABAP | `json`
|  [ZwdCSV](https://github.com/WegnerDan/ZwdCSV)   | CSV Parser and Generator for ABAP | `csv`
|  [abap-tbox-csvman](https://github.com/zenrosadira/abap-tbox-csvman) | ABAP CSV Manager - An easy-to-use and highly configurable tool to read and create CSV in ABAP | `csv`
|  [ABAP-HTML-Diff](https://github.com/Marc-Bernard-Tools/ABAP-HTML-Diff) | Library to highlight the content difference between two HTML strings (htmldiff) | `html`
|  [abap-string-map](https://github.com/sbcgua/abap-string-map) | String map primitive implementation on abap | `stringmap`
|  [abap_Filehandler](https://github.com/xamafe/abap_Filehandler) | Construction to handle Files in ABAP | `files`


<a name="dataproc" />

### 🪄 Data Processing
|   project      |     description      | tags |
|     :---:    |     :---:      | :---: |
|  [AES](https://github.com/Sumu-Ning/AES) | ABAP Utilities for AES/Rijndael encryption, decryption | `encryption`
|  [abap_jwt_generator](https://github.com/abapChaoLiu/abap_jwt_generator) | ABAP JWT Generator | `authentication`
|  [blowfish-abap](https://github.com/hhelibeb/blowfish-abap) | Blowfish encryption in ABAP | `encryption`
|  [abap-data-validator](https://github.com/hhelibeb/abap-data-validator) | A data validation tool | `validation`
|  [IDoc-with-ABAP-OOP](https://github.com/peyn/IDoc-with-ABAP-OOP) | IDoc-with-ABAP-OOP | `idoc`
|  [geohash-abap](https://github.com/hhelibeb/geohash-abap) | Geohash utitlies in ABAP | `encryption`
|  [abapPGP](https://github.com/larshp/abapPGP) | ABAP implementation of OpenPGP | `encryption`
|  [uid64](https://github.com/mkysoft/uid64) | UID-64 generator for ABAP | `uuid`
|  [GeoJson](https://github.com/se38/GeoJson) | ABAP Classes to create GeoJson strings | `json`
|  [abap-CSR](https://github.com/sandraros/abap-CSR) | ABAP Charset Recognizer (ICU) | `charset`
|  [abapITABOperations](https://github.com/joschkarick/abapITABOperations) | Advanced operations for internal tables in ABAP | `tables`

<a name="test" />

### 🧪 Testing
|   project      |     description      | tags |
|     :---:    |     :---:      | :---: |
|  [mockup_loader](https://github.com/sbcgua/mockup_loader)   | ABAP unit testing framework, prepare in Excel, reuse in abap code | `mocking`
|  [mockA](https://github.com/uweku/mockA)   | mockA is a free Mocking Framework for ABAP | `mocking`
|  [abapFaker](https://github.com/se38/abapFaker)   | ABAP Faker: generate fake test data | `mocking`
|  [abap_db_preparator](https://github.com/bunysae/abap_db_preparator)   |Avoid breaking tests with database preparation | `db prep`
|  [regression_test](https://github.com/germanysources/regression_test) | Create snapshots in ABAP | `db prep`

<a name="log" />

### 📝 Logging
|   project      |     description      | tags |
|     :---:    |     :---:      | :---: |
|  [ABAP-Logger](https://github.com/ABAP-Logger/ABAP-Logger)   | ABAP Logging as painless as any other language    | `logger`
|  [abap-fm-logger](https://github.com/hhelibeb/abap-fm-logger)   | A logger for function module (RFC) | `logger`
|  [abap-log-exporter](https://github.com/abap-observability-tools/abap-log-exporter)   | Exports SAP Netweaver logs to a log system of your choice. | `logs`
|  [abap-log](https://github.com/fabianlupa/abap-log)   | Logging library for ABAP | `logger`
|  [sap-usi-logging-api](https://github.com/SchwarzIT/sap-usi-logging-api)   | An easy-to-use, object-oriented encapsulation around the SAP application log (Transaction SLG1) | `logger`
|  [simbal](https://github.com/keremkoseoglu/simbal)   | Simple Business Application Log for ABAP | `logger`
|  [zcl_log_util](https://github.com/neooblaster/zcl_log_util)   | An another ABAP logging class allowing programs to focus on their functionality rather than being buried under lines of logging code | `logger`

<a name="git" />

### 📦 Packages & Versioning
|   project      |     description      | tags |
|     :---:    |     :---:      | :---: |
|  [abapGit](https://github.com/abapGit/abapGit)   | Git client for ABAP | `git`
|  [abapTimeMachine](https://github.com/abapinho/abapTimeMachine)   | ABAP Time Machine provides a much needed way to look at past versions of code in a consistent way. It also provides a sort of git-blame for ABAP (shows the request and author that last modified each line of code) | `versioning`

<a name="sci" />

### 🔎 Code Inspector / Linter / Performance
|   project      |     description      | tags |
|     :---:    |     :---:      | :---: |
|  [code-pal-for-abap](https://github.com/SAP/code-pal-for-abap)   | Highly configurable engine, fully integrated into the ABAP development framework ensuring Cloud’s built-in quality.    | `inspector`
|  [abapOpenChecks](https://github.com/larshp/abapOpenChecks)   | Open source checks for SAP Code Inspector / ABAP Test Cockpit | `inspector`
|  [abaplint](https://github.com/abaplint/abaplint)   | Standalone static analysis for ABAP | `linter`
|  [vscode-abaplint](https://github.com/abaplint/vscode-abaplint)   | Visual Studio Code abaplint extension | `linter`, `vsc`
|  [abaplint-sci-client](https://github.com/abaplint/abaplint-sci-client)   | ABAP part for running abaplint on ABAP backend | `linter`
|  [vscode-abap](https://github.com/larshp/vscode-abap) | ABAP syntax highlighting for Visual Studio Code | `vsc`
|  [abap-metrics-provider](https://github.com/abap-observability-tools/abap-metrics-provider) | Let's you use predefined or custom metrics to monitor your abap stack with a monitoring tool of your choice | `performance`
|  [upDOWNci](https://github.com/larshp/upDOWNci) | Upload and download SAP Code Inspector variants in XML format - ABAP | `inspector`
|  [ypinc](https://github.com/ypinc/ypinc) | ABAP perfomance primitives | `performance`

<a name="api" />

### 🐝 API & Services
|   project      |     description      | tags |
|     :---:    |     :---:      | :---: |
|  [ABAP-Swagger](https://github.com/larshp/ABAP-Swagger)   | Expose ABAP REST services with Swagger/openapi spec    | `api`
|  [abap-openapi](https://github.com/abap-openapi/abap-openapi)   | ABAP OpenAPI Client and Server generator in ABAP   | `api`
|  [abap-rest-api](https://github.com/pacroy/abap-rest-api)   | Simple ABAP REST API | `api`
|  [abapMQ](https://github.com/INVIXO/abapMQ)   | ABAP MQTT client | `mqtt`
|  [MQBA](https://github.com/MDJoerg/MQBA)   | Message Queue Broker ABAP | `mqtt`
|  [abapMQDaemons](https://github.com/se38/abapMQDaemons)   | Deamons for abapMQ | `mqtt`
|  [abapNTLM](https://github.com/larshp/abapNTLM)   | ABAP HTTP NTLM Client | `ntlm`
|  [abap-openapi-ui](https://github.com/geert-janklaps/abap-openapi-ui)   | OpenAPI / Swagger UI integration for SAP NetWeaver Gateway | `api`
|  [abap-http-agent](https://github.com/sbcgua/abap-http-agent)   | AHA - abap http agent, convenience wrapper over cl_http_client | `http`
|  [consume_rest_api_in_abap](https://github.com/s7oev/consume_rest_api_in_abap)   | Consuming REST APIs with (Cloud) ABAP | `api`
|  [consume_rest_api_in_abap](https://github.com/pacroy/abap-fluentd)   | Fluentd client in ABAP | `api`
|  [abap_kafka_rest_proxy](https://github.com/cesar-sap/abap_kafka_rest_proxy)   | ABAP to Confluent Kafka REST Proxy Connector | `proxy`

<a name="int" />

### 🖇️ Integration
|   project      |     description      | tags |
|     :---:    |     :---:      | :---: |
|  [vscode_abap_remote_fs](https://github.com/marcellourbani/vscode_abap_remote_fs) | Remote filesystem for ABAP systems | `vsc`
|  [ABAP-SDK-for-Azure](https://github.com/microsoft/ABAP-SDK-for-Azure) | ABAP Libraries for SAP native Integration with Azure Services | `azure`
|  [abap2gapps](https://github.com/ivanfemia/abap2gapps) | ABAP API for Google Apps integration | `google`
|  [abap2gsheet](https://github.com/techedgegroup-sap/abap2gsheet) | ABAP framework that abstract the Google Sheets API | `google`
|  [abap2oauth2](https://github.com/ivanfemia/abap2oauth2) | ABAP API for OAuth2 authentication | `authentication`
|  [ABAPFire](https://github.com/alborghetti/ABAPFire) | ABAP Firebase Client | `firebase`
|  [aws-lambda-abap-runtime](https://github.com/open-abap/aws-lambda-abap-runtime) | AWS Lambda ABAP custom runtime | `aws`
|  [proUBC](https://github.com/provideplatform/proUBC) | Open-source implementation of the PRVD Stack baseline middleware pattern for SAP, using ABAP | `baseline`
|  [abap-prometheus](https://github.com/pacroy/abap-prometheus) | Prometheus.io Client for ABAP | `prometheus`
|  [ABAP_DeepL_client](https://github.com/christianguenter2/ABAP_DeepL_client) | ABAP client for DeepL | `deepl`

<a name="adt" />

### 🌖 ADT & Eclipse
|   project      |     description      | tags |
|     :---:    |     :---:      | :---: |
|  [abap-adt-api](https://github.com/marcellourbani/abap-adt-api) | Abap Developer Tools client | `adt`
|  [ABAPFavories](https://github.com/fidley/ABAPFavorites) | ABAP Favorites Eclipse Plugin | `adt`
|  [ABAPQuickFix](https://github.com/fidley/ABAPQuickFix) | ABAPQuickFix | `adt`
|  [eclipse-abap-keywordcolors](https://github.com/FreHu/eclipse-abap-keywordcolors) | Customized ABAP keyword colors for eclipse | `adt`
|  [abap-search-tools](https://github.com/stockbal/abap-search-tools) | ABAP Search and Analysis tools (Backend for ADT Plugin) | `adt`
|  [abap-search-tools-ui](https://github.com/stockbal/abap-search-tools-ui) | Eclipse Plugin for ABAP Search and Analysis Tools | `eclipse`
|  [abap-tags-backend](https://github.com/stockbal/abap-tags-backend) | ADT Backend for ABAP Tags Plugin | `adt`
|  [ABAP-Project-Extensions](https://github.com/fidley/ABAP-Project-Extensions) | ABAP-Project-Extensions | `adt`

<a name="thr" />

### 🛤️ Threading
|   project      |     description      | tags |
|     :---:    |     :---:      | :---: |
|  [zconcurrency_api](https://github.com/victorizbitskiy/zconcurrency_api) | ABAP Development Utilities | `concurrency`
|  [zthread](https://github.com/xinitrc86/zthread) | Simple Thread implementation for ABAP. Based on JAVA Thread, its Runnable interface with some additional callback capabilities | `concurrency`
|  [promise](https://github.com/abapify/promise) | ABAP Promise + Async/Await implementation | `async`
|  [abap-threads](https://github.com/sbcgua/abap-threads) | abap threading utils | `threading`
|  [ABAPParallelizationService](https://github.com/BiberM/ABAPParallelizationService) | Parallelization Framework for ABAP Systems| `concurrency`
|  [ABAP-Simple-Async-Framework](https://github.com/MikeSidorochkin/ABAP-Simple-Async-Framework) | Simple Async Framework | `async`

<a name="gen" />

### 🧰 Generic Utilities
|   project      |     description      | tags |
|     :---:    |     :---:      | :---: |
|  [abap-dev-utilities](https://github.com/jrodriguez-rc/abap-dev-utilities) | ABAP Development Utilities | `tools`
|  [abaK](https://github.com/abapinho/abaK) | ABAP constants done right | `constants`
|  [open-table-maintenance](https://github.com/open-abap/open-table-maintenance) | Multi target low footprint ABAP table maintenance | `table maintenance`
|  [zapcommander](https://github.com/tricktresor/zapcommander) | Filecommander (Norton-Commander-Clone) for SAP-Systems (ABAP) | `commander`
|  [Customers](https://github.com/fidley/Customers) | Wrapper for CMD_EI_API classes | `customers`
|  [ABAP-Commons](https://github.com/HannesRempel/ABAP-Commons) | Providing reusable ABAP components | `tools`
|  [Featuretoggle](https://github.com/btc-ag/Featuretoggle) | A simple, lightweight feature toggle framework for ABAP | `toggle`
|  [abap-feature-toggle](https://github.com/raketenstart-abap/abap-feature-toggle) | Feature toggle for ABAP | `toggle`
|  [zscv_search_cds_views](https://github.com/alwinvandeput/zscv_search_cds_views) | ABAP Search CDS Views Tool | `cds`
|  [abap_seltab_to_where](https://github.com/abapChaoLiu/abap_seltab_to_where) | Convert ABAP range tables to SQL where clause| `sql`
|  [zcx_return3](https://github.com/alwinvandeput/zcx_return3) | ABAP exception lclass for handling all kind of procedural error messages | `sql`
|  [elitechat](https://github.com/AntonSikidin/elitechat) | abap based instant messaging | `chat`
|  [zspool_pdf](https://github.com/victorizbitskiy/zspool_pdf) | Submitting a report to the spool and receiving PDF | `pdf`
|  [mime_editor](https://github.com/larshp/mime_editor) | SMIM editor in ABAP | `mime`
|  [ABAP_TRANSLATION_HUB](https://github.com/DerGuteWolf/ABAP_TRANSLATION_HUB) | Push Object List to Translation Hub and Pull Translations | `translation`
|  [abap_w3mi_poller](https://github.com/sbcgua/abap_w3mi_poller) | A tool to poll file change and upload changed files automatically as W3MI object | `polling`
|  [synchronize-SAP-GUI-favorites](https://github.com/Keller-Michael/synchronize-SAP-GUI-favorites) | simple tool to synchronize SAP GUI favorites between systems and clients | `gui`
|  [abap-reference](https://github.com/kkayacan/abap-reference) | Samples and utilities for SAP development | `tools`
|  [ABAPCodeVault](https://github.com/raymondbonnmendoza/ABAPCodeVault) | Reusable code, module specific sample programs, useful FMs, classes and info for ABAP developers | `tools`
|  [abap-archiving-engine](https://github.com/00500500/abap-archiving-engine) | ABAP Archiving Engine | `archiving`
|  [abap-tbox-splitter](https://github.com/zenrosadira/abap-tbox-splitter) | ABAP utility class to easily split an internal table in different sub-tables | `tools`
|  [Vise_for_ABAP](https://github.com/uweku/Vise_for_ABAP) | Vise for ABAP | `refactoring`
|  [user-exit-scanner](https://github.com/MDagni/user-exit-scanner) | Abap user-exit scanner | `finder`
|  [ABAP-Check-Translations](https://github.com/juansebastiansoto/ABAP-Check-Translations) | Report to check the translations elements in ABAP | `translation`
|  [ZFPM_TOOLS](https://github.com/boy0korea/ZFPM_TOOLS#english) | FPM Tools for developers | `fpm`
|  [MBT-Command-Field](https://github.com/Marc-Bernard-Tools/MBT-Command-Field) | The world's first enhancement for the SAP® GUI command field | `gui`
|  [abapTechDocu](https://github.com/victorizbitskiy/abapTechDocu) | A tool for creating technical documentation | `tools`

<a name="sam" />

### 👩‍🎓 Samples & Learning
|   project      |     description      | tags |
|     :---:    |     :---:      | :---: |
|  [abap-platform-rap-opensap](https://github.com/SAP-samples/abap-platform-rap-opensap)   | Samples for the openSAP course "Building Apps with the ABAP RESTful Application Programming model (RAP)."     | `abap RAP`
|  [abap-platform-refscen-flight](https://github.com/SAP-samples/abap-platform-refscen-flight) | SFlight is back! This is the Flight Reference Scenario for the ABAP RESTful Application Programming Model. | `abap RAP`
|  [abap-platform-rap-workshops](https://github.com/SAP-samples/abap-platform-rap-workshops) | This repository contains materials for workshops about the ABAP RESTful Application Programming Model (RAP). | `abap RAP`
|  [abap-cheat-sheets](https://github.com/SAP-samples/abap-cheat-sheets) | Explore ABAP syntax in a nutshell supported by executable demo examples | `cheat-sheet`
|  [ABAPDesignPattern](https://github.com/moreus/ABAPDesignPattern) | 23 Design Patterns in ABAP | `oop`
|  [ABAP-OOP-Library](https://github.com/rvanmil/ABAP-OOP-Library) | ABAP Object-oriented programming Library | `oop`
|  [abap_oo_patterns](https://github.com/SchwarzIT/abap_oo_patterns) | Example implementation of OO design patterns in ABAP | `oop`
|  [excrcism/abap](https://github.com/exercism/abap) | Exercism exercises in ABAP | `exercises`
|  [New-ABAP-Tips-Tricks](https://github.com/suriyarasu/New-ABAP-Tips-Tricks) | This repository contains new ABAP syntax for S/4HANA Development| `language`
|  [gladius](https://github.com/tricktresor/gladius) | Learning and challenging with ABAP Unit Test Framework | `testing`
|  [DesignByContract](https://github.com/hardyp/DesignByContract) | Design by Contract in ABAP | `oop`

<a name="doc" />

### ℹ️ Documentation & Informations
|   project      |     description      | tags |
|     :---:    |     :---:      | :---: |
|  [Eclipse_ADT_info_hub](https://github.com/Keller-Michael/Eclipse_ADT_info_hub) | collection of helpful information about ABAP Development Tools | `info`
|  [ABAP_starter](https://github.com/Keller-Michael/ABAP_starter) | 🚀 very basic information to start working with ABAP | `info`
|  [abap-docs](https://github.com/eduardocopat/abap-docs) | Enhanced ABAP documentation | `docs`
|  [CleanABAP](https://github.com/Freedomanda/CleanABAP) | Guideline to improve the ABAP code quality | `language`
