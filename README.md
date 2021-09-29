# rpaproject-si-sm-uipath
LG전자 RPA 프로젝트 SI/SM

해당 RPA 프로젝트 폴더 구성은 현재 LG전자에서 운영중인 Framework으로(UIPATH community버전에서 무료 제공하는 framework와 동일), LG전자 보안으로 인해 폴더 구조만 간략히 나타내었습니다.

RPA 프로젝트 개발환경은 가상PC(VM환경), 운영환경 Bot, Orchestrator로 구성되어있습니다.
가상PC(VM환경)과 운영환경 Bot은 동일한 환경으로 구성되어 있고, 현업과 협의를 통해 프로세스(과제)를 VM환경에서 uipath를 통해 개발합니다.

개발이 완료된 프로세스는 Orchestrator를 통해 운영반영할 Bot과 trigger를 통한 프로세스가 수행할 배치시간을 설정합니다.

Orchestrator에서 운영반영된 프로세스의 수행여부를 확인가능합니다.

