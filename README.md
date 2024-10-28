# Open Targets release snapshots

This repo contains snapshots for all the components used to generate a release of
the Open Targets Platform.

To get the latest release, use the following command:

```bash
git clone git@github.com:opentargets/ot-snapshots.git --recurse-submodules
```

To get a particular release, use the following command:

```bash
git clone git@github.com:opentargets/ot-snapshots.git
cd ot-snapshots
git checkout <release-tag>
git submodule update --init --recursive
```


## Components

- [curation](https://github.com/opentargets/curation) — Open Targets curation repository
- [evidence_datasource_parsers](https://github.com/opentargets/evidence_datasource_parsers) — Open Targets internal evidence generation
- [json_schema](https://github.com/opentargets/json_schema) — Schemas of the Open Targets Platform data models
- [OnToma](https://github.com/opentargets/OnToma) — Python module which maps the disease or phenotype terms to EFO
- [ot-ai-api](https://github.com/opentargets/ot-ai-api) — Open Targets AI API router
- [ot-ui-apps](https://github.com/opentargets/ot-ui-apps) — Open Targets web applications
- [platform-api](https://github.com/opentargets/platform-api) — Open Targets Platform API
- [platform-input-support](https://github.com/opentargets/platform-input-support) — Open Targets input data acquisition application
- [platform-etl-backend](https://github.com/opentargets/platform-etl-backend) — Open Targets Pipeline ETL process
- [platform-output-support](https://github.com/opentargets/platform-output-support) — Open Targets output data generation application
- [terraform-google-opentargets](https://github.com/opentargets/terraform-google-opentargets-platform) — Open Targets Infrastructure definition

## Copyright

Copyright 2014-2024 EMBL - European Bioinformatics Institute, Genentech, GSK, MSD, Pfizer, Sanofi and Wellcome Sanger Institute

This software was developed as part of the Open Targets project. For more information please see: http://www.opentargets.org

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
