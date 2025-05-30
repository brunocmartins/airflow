
 .. Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

 ..   http://www.apache.org/licenses/LICENSE-2.0

 .. Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.

 .. NOTE! THIS FILE IS AUTOMATICALLY GENERATED AND WILL BE OVERWRITTEN!

 .. IF YOU WANT TO MODIFY THIS FILE, YOU SHOULD MODIFY THE TEMPLATE
    `PROVIDER_COMMITS_TEMPLATE.rst.jinja2` IN the `dev/breeze/src/airflow_breeze/templates` DIRECTORY

 .. THE REMAINDER OF THE FILE IS AUTOMATICALLY GENERATED. IT WILL BE OVERWRITTEN!

Package apache-airflow-providers-edge3
--------------------------------------

Handle edge workers on remote sites via HTTP(s) connection and orchestrates work over distributed sites


This is detailed commit list of changes for versions provider package: ``edge3``.
For high-level changelog, see :doc:`package information including changelog <index>`.



1.0.0
.....

Latest change: 2025-04-05

==================================================================================================  ===========  ============================================================================================================================================================
Commit                                                                                              Committed    Subject
==================================================================================================  ===========  ============================================================================================================================================================
`ed93c3f697 <https://github.com/apache/airflow/commit/ed93c3f6970eb207c727b2f4a1da295fa4c74cc3>`__  2025-04-05   ``fix: use pydantic model for edge worker registration response (#48821)``
`1c81120869 <https://github.com/apache/airflow/commit/1c81120869459dfe40708d750dcf740cc9411cdd>`__  2025-04-05   ``Update Edge Provider docs prior 1.0.0 release (#48814)``
`e391a58c29 <https://github.com/apache/airflow/commit/e391a58c297e7bdd6dd071a563e0d887c2b5b54c>`__  2025-04-05   ``Cleanup redundant hostname lookup and migrate to core hostname function. (#48813)``
`6105452cb5 <https://github.com/apache/airflow/commit/6105452cb50a8a78c0b7ac52d80ea364b110723a>`__  2025-04-04   ``edge worker reports hostname as task runner (#48783)``
`d4473555c0 <https://github.com/apache/airflow/commit/d4473555c0e7022e073489b7163d49102881a1a6>`__  2025-04-02   ``Simplify tooling by switching completely to uv (#48223)``
`47002feacd <https://github.com/apache/airflow/commit/47002feacd8aaf794b47c2dd241aa25068354a2a>`__  2025-03-30   ``Upgrade ruff to latest version (#48553)``
`69ae9e33f8 <https://github.com/apache/airflow/commit/69ae9e33f81944403cf93b515b8702db9071f930>`__  2025-03-28   ``Update fast-api generated code after Pydantic upgrade (#48484)``
`6adb2dbae4 <https://github.com/apache/airflow/commit/6adb2dbae47341eb61dbc62dbc56176d9aa83fd9>`__  2025-03-25   ``Upgrade providers flit build requirements to 3.12.0 (#48362)``
`545bf451d4 <https://github.com/apache/airflow/commit/545bf451d47a9a5335ccf7858dee22ff88ab4de1>`__  2025-03-21   ``Setting Airflow context Environment variables for operators (#47644)``
`243fe86d4b <https://github.com/apache/airflow/commit/243fe86d4b3e59bb12977b3e36ca3f2ed27ca0f8>`__  2025-03-21   ``Move airflow sources to airflow-core package (#47798)``
`59555b4f53 <https://github.com/apache/airflow/commit/59555b4f5352a61423e824fd187b19fcbb78a319>`__  2025-03-17   ``Fix: JWT token auth in Airflow 3 beta as JWT mechanism changed (#47835)``
`935d2831fe <https://github.com/apache/airflow/commit/935d2831fe8fd509b618a738bf00e0c34e186e11>`__  2025-03-15   ``Remove links to x/twitter.com (#47801)``
`74f4860bb1 <https://github.com/apache/airflow/commit/74f4860bb12571f42e25f77c2f992bd0c7f2a70a>`__  2025-03-14   ``Re-work JWT Validation and Generation to use public/private key and official claims (#46981)``
`d1a44f0d58 <https://github.com/apache/airflow/commit/d1a44f0d5825d12e486727dfe0bab9c977c97a31>`__  2025-03-11   ``Heartbeat timeout docs (#46257)``
`8cc9f1fca9 <https://github.com/apache/airflow/commit/8cc9f1fca9343768e9aa7bb4c802e7d2fc109719>`__  2025-03-07   ``Relocate airflow.auth to airflow.api_fastapi.auth (#47492)``
`e4002c3305 <https://github.com/apache/airflow/commit/e4002c3305a757f5926f96c996e701e8f998a042>`__  2025-03-05   ``Move tests_common package to devel-common project (#47281)``
`bb8d465f22 <https://github.com/apache/airflow/commit/bb8d465f221864e4fd84ee5ed5b0bbb524c95d50>`__  2025-03-05   ``Clean Leftovers of RemovedInAirflow3Warning (#47264)``
`8f4fc4f107 <https://github.com/apache/airflow/commit/8f4fc4f107697079841c1f63c3feb00b58b8c12a>`__  2025-03-04   ``Remove 'airflow.www' module (#47318)``
`0f21f0ab42 <https://github.com/apache/airflow/commit/0f21f0ab426257d2258a886194591973d7e1e36b>`__  2025-03-03   ``Move 'airflow.www.auth' to 'airflow.providers.fab.www.auth' (#47307)``
`1addb55154 <https://github.com/apache/airflow/commit/1addb55154fbef31bfa021537cfbd4395696381c>`__  2025-02-28   ``Improve documentation for updating provider dependencies (#47203)``
`647b39d2e9 <https://github.com/apache/airflow/commit/647b39d2e9b2a173369e8cb60c541717a4238236>`__  2025-02-28   ``[Edge] Export ti.success and ti.finish metrics from edge worker (#47063)``
`0fab3b2c29 <https://github.com/apache/airflow/commit/0fab3b2c29134c3c4b6bf9ae20907b6d884b0464>`__  2025-02-27   ``Edge worker maintenance mode can be set from cli (#47140)``
`51415547d6 <https://github.com/apache/airflow/commit/51415547d681942ec389f143125e8f9f163d690c>`__  2025-02-26   ``Remove old UI and webserver (#46942)``
`c6c4f95ed9 <https://github.com/apache/airflow/commit/c6c4f95ed9e3220133815b9126c135e805637022>`__  2025-02-25   ``Add legacy namespace packages to airflow.providers (#47064)``
`dbf8bb4092 <https://github.com/apache/airflow/commit/dbf8bb409223687c7d2ad10649a92d02c24bb3b4>`__  2025-02-24   ``Remove extra whitespace in provider readme template (#46975)``
`2d267ddcad <https://github.com/apache/airflow/commit/2d267ddcad4c48b50cbf12f4ff68f2ec9c8f017a>`__  2025-02-21   ``Move execution_api_server_url config to the core section (#46969)``
`b28c336e8b <https://github.com/apache/airflow/commit/b28c336e8b7aa1d69c0f9520b182b1b661377337>`__  2025-02-21   ``Upgrade flit to 3.11.0 (#46938)``
`3b5a503a26 <https://github.com/apache/airflow/commit/3b5a503a26e02fd18352081851eff751cdc0493d>`__  2025-02-18   ``[EDGE]Fix maintenance states during shut down (#46861)``
`165ea9ed0c <https://github.com/apache/airflow/commit/165ea9ed0c42d1dc06b373e62a5c6cbaa27b5633>`__  2025-02-17   ``[EDGE]CLI allows to retrieve status of worker (#46818)``
`4365e31f9b <https://github.com/apache/airflow/commit/4365e31f9b74b3035aefb2d64520fca5b5e05dfe>`__  2025-02-17   ``Edge worker stop command can wait for processes to terminate (#46816)``
`4d5846f58f <https://github.com/apache/airflow/commit/4d5846f58fe0de9b43358c0be75dd72e968dacc4>`__  2025-02-16   ``Move provider_tests to unit folder in provider tests (#46800)``
`4c031cb855 <https://github.com/apache/airflow/commit/4c031cb855f455c94eb91c6be3adeec638a9d3d7>`__  2025-02-15   ``Remove assert in example DAG (#46794)``
`e027457a24 <https://github.com/apache/airflow/commit/e027457a24d0c6235bfed9c2a8399f75342e82f1>`__  2025-02-15   ``Removed the unused provider's distribution (#46608)``
`c7c3de5e77 <https://github.com/apache/airflow/commit/c7c3de5e7774f133727393b56c29e8f7ea9ddd61>`__  2025-02-14   ``Feature/minor modification on edge worker maintenance comment (#46755)``
`da254edf7e <https://github.com/apache/airflow/commit/da254edf7e2998b0080eb1325ec7840fbdf1b5bb>`__  2025-02-13   ``Feature/edge worker maintenance logs user (#46712)``
`0047a6886a <https://github.com/apache/airflow/commit/0047a6886a12478dc30fe76e7192fc837b118001>`__  2025-02-11   ``change listener API, add basic support for task instance listeners in TaskSDK, make OpenLineage provider support Airflow 3's listener interface (#45294)``
`c2efb867b9 <https://github.com/apache/airflow/commit/c2efb867b93feba81bcf054e2cb4b21dffbdb7dc>`__  2025-02-10   ``Bugfix/fix sql query in edge executor (#46620)``
`bef48242f8 <https://github.com/apache/airflow/commit/bef48242f8143f88a1805803ab30aad1bc6c2e7b>`__  2025-02-10   ``Feature/enable comment on maintenance mode (#46519)``
`5f14679669 <https://github.com/apache/airflow/commit/5f14679669b8fd121f41d73f93bce1df78c3efc0>`__  2025-02-05   ``Undoing the retryhttp limitation (<1.3.0) (#46470)``
`0a61ac80aa <https://github.com/apache/airflow/commit/0a61ac80aa66835ce4db3b28f829256a33ed8590>`__  2025-02-05   ``Bugfix/edge worker restarts on version mismatch (#46453)``
`6059e8434d <https://github.com/apache/airflow/commit/6059e8434d3ddb7ed0a98bf702b403024a037237>`__  2025-02-05   ``Implement worker deletion and proper scrf handling (#46452)``
`699171a6d4 <https://github.com/apache/airflow/commit/699171a6d455cfd66ecc81fd5638129d06317826>`__  2025-02-05   ``Limiting retryhttp to not use 1.3.0 to fix CI mypy checks (#46446)``
`b90b3938c6 <https://github.com/apache/airflow/commit/b90b3938c66947c9e98c78693cb9bef7689478ef>`__  2025-02-04   ``[EDGE] worker remembers maintenance on restart (#46416)``
`e6ea6709bb <https://github.com/apache/airflow/commit/e6ea6709bbd8ba7c024c4f75136a0af0cf9987b0>`__  2025-02-04   ``Moving EmptyOperator to standard provider (#46231)``
`f0135276f1 <https://github.com/apache/airflow/commit/f0135276f1c9b94d0c8e3fc8d56f82c42124cc46>`__  2025-02-03   ``[EDGE]Enable edge worker maintenance mode (#45958)``
`03c4966df4 <https://github.com/apache/airflow/commit/03c4966df412272d1769e25379b221faf86ac2f7>`__  2025-01-31   ``AIP-72: Move DAG Params to Task SDK (#46176)``
`29b9e8ea10 <https://github.com/apache/airflow/commit/29b9e8ea10de7a82ad40a7a2160c64a84004a45e>`__  2025-01-25   ``move standard, alibaba and common.sql provider to the new structure (#45964)``
`4dda6ba8c0 <https://github.com/apache/airflow/commit/4dda6ba8c01912db2c2a6518dacd062b10ebf1e0>`__  2025-01-23   ``Move new provider tests to "provider_tests" submodule (#45955)``
`2a1f17d052 <https://github.com/apache/airflow/commit/2a1f17d0521fd82736c76dfe05d0695505ffffec>`__  2025-01-22   ``Add script to move providers to the new directory structure (#45945)``
`2193be2a5e <https://github.com/apache/airflow/commit/2193be2a5e53760ae00d1b85c825087e995f8eb1>`__  2025-01-22   ``Fix failures on main related to DagRun validation (#45917)``
`90af41071e <https://github.com/apache/airflow/commit/90af41071e2fc4c0bdf604b09983bdc641466863>`__  2025-01-20   ``Fix authentication for cases where webserver.base_url is not defined and worker is not using localhost in 2.10. (#45785)``
`25aeb1166e <https://github.com/apache/airflow/commit/25aeb1166e6e8d093892ad3a7b1a341375b0cf51>`__  2025-01-20   ``move Celery provider to new provider code structure (#45786)``
`08d0273c1a <https://github.com/apache/airflow/commit/08d0273c1a88333f504913ae7b35ddb0414f24b1>`__  2025-01-20   ``Use Protocol for 'OutletEventAccessor' (#45762)``
`e2da4c7a0a <https://github.com/apache/airflow/commit/e2da4c7a0ad5688f54c0fbcfa8075eff8bbf514e>`__  2025-01-19   ``Move Edge to new provider structure (#45783)``
`6d048c43f0 <https://github.com/apache/airflow/commit/6d048c43f0753d96976f3c9e72262cfe3b27d052>`__  2025-01-14   ``Run the task with the configured dag bundle (#44752)``
`f616c62209 <https://github.com/apache/airflow/commit/f616c62209d6b51d293ecf6f5c900f89a7fdc3a3>`__  2025-01-15   ``AIP-72: Support better type-hinting for Context dict in SDK  (#45583)``
`1cf1d62840 <https://github.com/apache/airflow/commit/1cf1d628404ab62f979d2b0d9936ca5af001f44f>`__  2025-01-14   ``Move first provider (airbyte) to a separate project (#45259)``
`ead9386a68 <https://github.com/apache/airflow/commit/ead9386a68bb104e5afafca3c5d768afa27dc89d>`__  2025-01-12   ``AIP-72 Add Task Scheduling Metadata to TaskInstance (#45008)``
`0399381969 <https://github.com/apache/airflow/commit/03993819690fe8b98cdd8a6540bc6a107cdb9a63>`__  2025-01-07   ``Support Task execution interface (AIP-72) in Airflow 3 in EdgeExecutor (#44982)``
`03659e4ece <https://github.com/apache/airflow/commit/03659e4ece38ef82f26b4c797ec053f0462c6324>`__  2025-01-05   ``Document deployment of Edge Worker on Windows (#45403)``
`1e04741aeb <https://github.com/apache/airflow/commit/1e04741aeb9dd14ea1794138c10de041df794c54>`__  2025-01-04   ``Make Edge API retries configurable (#44536)``
`ef004def30 <https://github.com/apache/airflow/commit/ef004def3035fad4174043ef37db85f3ab93add3>`__  2024-12-18   ``Add failure test to Edge integration test (#45031)``
`2a33da0246 <https://github.com/apache/airflow/commit/2a33da0246c811a98d5cdaf0af2bcca0dee8556a>`__  2024-12-18   ``Remove references to AIRFLOW_V_2_9_PLUS (#44987)``
`83da311e4c <https://github.com/apache/airflow/commit/83da311e4ce5a7965b2e1c412941a8f26ad8225e>`__  2024-12-16   ``Replaced null value with question mark in edge logs (#44957)``
`707c564ad3 <https://github.com/apache/airflow/commit/707c564ad3d6a56421f451c5f29a429d0395766f>`__  2024-12-16   ``Fix edge doc merge conflict artefact (#44948)``
`007e8876b3 <https://github.com/apache/airflow/commit/007e8876b3484f5d743c2c78ee4b23c9ffbb3dc1>`__  2024-12-13   ``Revert removal of Pydantic model support from PR 44552 to restore compatibility with Airflow 2.10 (#44921)``
`694cbbb719 <https://github.com/apache/airflow/commit/694cbbb719a1b0fdc26b6378b99507c43868eaa6>`__  2024-12-13   ``Keep executor running in sync with edge job table (#44916)``
`fb9aaa3548 <https://github.com/apache/airflow/commit/fb9aaa3548d345c97373c33c7c295faadfac749c>`__  2024-12-13   ``Handle purging of restarting edge jobs (#44914)``
`8af1bbdf25 <https://github.com/apache/airflow/commit/8af1bbdf25e2650e617d456f729d1d4f46465524>`__  2024-12-12   ``Remove Pydanitc models introduced for AIP-44 (#44552)``
`490b5e816b <https://github.com/apache/airflow/commit/490b5e816b804f338b0eb97f240ae874d4e15810>`__  2024-12-10   ``Consistent way of checking Airflow version in providers (#44686)``
`db14b8c1c0 <https://github.com/apache/airflow/commit/db14b8c1c0f99c2be2b767e05cf5118ffd910cb7>`__  2024-12-09   ``[Edge] Fix edge worker api support none default base api url (#44732)``
`4be8e4db3c <https://github.com/apache/airflow/commit/4be8e4db3c96e8ad3d51222e1a046c08513ec8bb>`__  2024-12-06   ``Make edge executor db access multi instance save (#44716)``
`887fa1ee73 <https://github.com/apache/airflow/commit/887fa1ee7317c35083b7c3823de6dcd145364972>`__  2024-12-04   ``Revert "Revert Edge Datamodelling for Pydantic problems in Py3.9 (#44550)" (#44584)``
`3413b12889 <https://github.com/apache/airflow/commit/3413b12889a50250ddb58548e39c638f99cb055b>`__  2024-12-02   ``Revert Edge Datamodelling for Pydantic problems in Py3.9 (#44550)``
`8c019cf590 <https://github.com/apache/airflow/commit/8c019cf5907cdba320bea7bf50c7fd341ca8ee49>`__  2024-12-02   ``Remove all remnants of "internal_api_call" (#44551)``
`0d98e2b052 <https://github.com/apache/airflow/commit/0d98e2b052066c92b88a7b7d16449f4dc36d1b2a>`__  2024-12-01   ``Migrate Edge calls for Worker to FastAPI part 4 - Cleanup (#44434)``
`161beebc77 <https://github.com/apache/airflow/commit/161beebc771329ad0525f4df39b46c6f72776034>`__  2024-12-01   ``Migrate Edge calls for Worker to FastAPI part 3 - Jobs routes (#44433)``
`b003e6c949 <https://github.com/apache/airflow/commit/b003e6c949971be2a25db212756689f0a0ee4562>`__  2024-12-01   ``Remove mypy errors from semantic merge problems due to Internal API removal (#44528)``
`1b67b4386c <https://github.com/apache/airflow/commit/1b67b4386c91ddcb7dc80fcce4d0fe0b701efc78>`__  2024-11-30   ``Migrate Edge calls for Worker to FastAPI part 2 - Logs routes (#44330)``
`6057a2e04e <https://github.com/apache/airflow/commit/6057a2e04e2488681f0874d236f26385c084a7ac>`__  2024-11-30   ``Migrate Edge calls for Worker to FastAPI part 1 - Worker routes (#44311)``
`55e419e95a <https://github.com/apache/airflow/commit/55e419e95ab027d161cef95571300af9b2c81a0d>`__  2024-11-30   ``Remove AIP-44 from Job (#44493)``
`84907f16af <https://github.com/apache/airflow/commit/84907f16af99e455951ac95d36fba5a966ccf763>`__  2024-11-30   ``Remove API-44 methods from method map (#44494)``
`eee6919ff6 <https://github.com/apache/airflow/commit/eee6919ff64412156d821dcebc96a58efafd7786>`__  2024-11-29   ``fix(provider/edge): add back mising method map (#44468)``
`e9f544cc3f <https://github.com/apache/airflow/commit/e9f544cc3fb1ac3d7709b3c54804dd6fdd510eca>`__  2024-11-28   ``Remove AIP-44 configuration from the code (#44454)``
`497566ff5d <https://github.com/apache/airflow/commit/497566ff5de6593b1c6f5f54c2c2404c1b9186c3>`__  2024-11-28   ``Edge worker connected state is sent to DB based on worker sate (#44447)``
`90442e8577 <https://github.com/apache/airflow/commit/90442e85775eaffb2c9936ad7859899ef625d619>`__  2024-11-27   ``[Edge] Edge worker supports capacity handling instead of concurrency (#43737)``
`b134ed089b <https://github.com/apache/airflow/commit/b134ed089b74021858ded34dbc021ef053427650>`__  2024-11-26   ``Remove Pydantic 2.10.0/2.10.1 workaround (#44400)``
`6748b2a5f7 <https://github.com/apache/airflow/commit/6748b2a5f712927ca1ce32f7f3c44ce4e4347525>`__  2024-11-26   ``Fix edge in rare conditions that task state can not be reported as cleaned in parallel (#44314)``
`1275fec92f <https://github.com/apache/airflow/commit/1275fec92fd7cd7135b100d66d41bdcb79ade29d>`__  2024-11-24   ``Use Python 3.9 as target version for Ruff & Black rules (#44298)``
`e5de5506d5 <https://github.com/apache/airflow/commit/e5de5506d54aeacbd78da319a5975411db4b03cd>`__  2024-11-23   ``Fix the Show Down text (#44292)``
`d79c6c21f2 <https://github.com/apache/airflow/commit/d79c6c21f2d571bae236419bad87bc48bf9c97ce>`__  2024-11-22   ``[edge] Clean up of dead tasks in edge_jobs table  (#44280)``
`8f567ec4b9 <https://github.com/apache/airflow/commit/8f567ec4b9a7df548f636527a20379cc58bbe10e>`__  2024-11-22   ``Lower-bind pydantic to 2.10.1 (#44284)``
`4863383dca <https://github.com/apache/airflow/commit/4863383dca5524bc7d0c27cdbb23b4e13c17eaf4>`__  2024-11-18   ``Update Edge Executor documentation to current state (#44119)``
`f0dcfd65bd <https://github.com/apache/airflow/commit/f0dcfd65bd59df76c70944b73d7a3aa2075a9d93>`__  2024-11-17   ``Correct type hinting for RPC API endpoint in EdgeWorker for FastAPI (#44097)``
`76ce15a4c3 <https://github.com/apache/airflow/commit/76ce15a4c322bb8d5f49dd384e055b782118c985>`__  2024-11-16   ``Fix Pydantic model in Airflow 2.10 back-compat tests for Edge (#44099)``
`fb758ae56b <https://github.com/apache/airflow/commit/fb758ae56bce9b7c3050dc0f73549be985e14e6d>`__  2024-11-16   ``Migrate Edge Worker backend to FastAPI (#43865)``
`00ef940445 <https://github.com/apache/airflow/commit/00ef940445293ee3962895ee9f72bdbae7f0dabb>`__  2024-11-13   ``[edge] Fixed UnicodeDecodeError during log file upload of Edge worker (#43954)``
`d23fe09ab1 <https://github.com/apache/airflow/commit/d23fe09ab1d870ec6024c537b0c53588df6df80a>`__  2024-11-12   ``[Edge]Add child processes to separate process group than main (#43927)``
`12c7dd429c <https://github.com/apache/airflow/commit/12c7dd429c467dbf0c0549fe1ddfc4af3d1d9e1e>`__  2024-11-11   ``[Edge]Worker UI link beautification (#43869)``
`d41c859cf3 <https://github.com/apache/airflow/commit/d41c859cf3391d5a918552e96542bccc5c3e2bef>`__  2024-11-06   ``Remove schedule downstream tasks after execution (aka "mini scheduler") (#43741)``
`26eaeedb4d <https://github.com/apache/airflow/commit/26eaeedb4dcd6f8f3e857351a2be6df8cd19293c>`__  2024-11-06   ``Beautify queues output on overviewer page (#43734)``
`80f442dc29 <https://github.com/apache/airflow/commit/80f442dc29d5b2714005965b389f2e092b7686ad>`__  2024-11-01   ``Remove warning about missing config in edge plugin loading (#43596)``
`06088a3abc <https://github.com/apache/airflow/commit/06088a3abcbb46533e74de360746db766d50cf66>`__  2024-10-31   ``Standard provider python operator (#42081)``
`96aae9718f <https://github.com/apache/airflow/commit/96aae9718f51af1414ba90ac082d74e8ceaaf34c>`__  2024-10-29   ``Edge worker graceful shutdown on version mismatch (#43462)``
`752f933102 <https://github.com/apache/airflow/commit/752f933102754f330c4ffb5a545a4f4de93eef78>`__  2024-10-25   ``EdgeWorker support log file upload in chunks (#43374)``
`45caab1570 <https://github.com/apache/airflow/commit/45caab1570b4117394b8c0b4774d24b194e2d973>`__  2024-10-24   ``[Edge] Add metrics export and reset state of Edge Worker after worker timeout (#43215)``
`3b0cb76b6d <https://github.com/apache/airflow/commit/3b0cb76b6d8c4dcbf0c4b1425a16d73660bb3f1f>`__  2024-10-23   ``Made usage of Path explicit for Edge Worker pid files (#43308)``
`c5776c5550 <https://github.com/apache/airflow/commit/c5776c5550daae1531cf80104598ddcf36eb12d0>`__  2024-10-22   ``Fix Edge Worker handles orphaned PID files (#43153)``
`776764276f <https://github.com/apache/airflow/commit/776764276f6d66cef844a53d3ee03d72d4116bd7>`__  2024-10-18   ``Provider package Edge: Edge worker supports queue handling (#43115)``
`76c8470047 <https://github.com/apache/airflow/commit/76c84700476da07883ecdd4dbee0cc57bcf7e9ac>`__  2024-10-18   ``AIP-69: Add leftover glue of all pieces to Edge Provider (#42051)``
`824ec4a80d <https://github.com/apache/airflow/commit/824ec4a80d41290894223dac3ed43eacf924a1d5>`__  2024-10-17   ``AIP-69: Add Executor to Edge Provider (#42048)``
`857ca4c06c <https://github.com/apache/airflow/commit/857ca4c06c9008593674cabdd28d3c30e3e7f97b>`__  2024-10-09   ``Split providers out of the main "airflow/" tree into a UV workspace project (#42505)``
`a5ffbbda17 <https://github.com/apache/airflow/commit/a5ffbbda17450a5c99037b292844087119b5676a>`__  2024-10-09   ``Standard provider bash operator (#42252)``
`741276c6c6 <https://github.com/apache/airflow/commit/741276c6c649c2b05816813a4357c1f1fe37f587>`__  2024-10-03   ``Update min version of Pydantic to 2.6.4 (#42694)``
`4bff12150b <https://github.com/apache/airflow/commit/4bff12150b19a4a5d08d2f2f40b584106406e106>`__  2024-10-03   ``AIP-69: Add API and Plugin to Edge Provider (#42049)``
`3390bfbf98 <https://github.com/apache/airflow/commit/3390bfbf98c4ea4324ebfc16bd04e84e66daf73f>`__  2024-09-24   ``AIP-69: Add CLI to Edge Provider (#42050)``
`788b9c486b <https://github.com/apache/airflow/commit/788b9c486bf9e42fb4b10a30edef7f536bb873d6>`__  2024-09-16   ``Add DB models for Edge Provider (#42047)``
`0d4b00a140 <https://github.com/apache/airflow/commit/0d4b00a140572ceb78f840a9c5c3acd47340ed85>`__  2024-09-11   ``Adding bare/empty provider package for AIP-69 as starting point (#42046)``
==================================================================================================  ===========  ============================================================================================================================================================
