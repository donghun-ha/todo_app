# todo_app
Flutter Task Management App

이 Flutter 애플리케이션은 간단하면서도 효과적인 작업 관리 도구를 제공합니다. 사용자는 작업을 생성하고, 이 작업을 다양한 시간 간격으로 알림을 받을 수 있도록 설정할 수 있습니다. 
이 프로젝트는 Flutter 3.7.0 버전으로 업그레이드된 비디오 튜토리얼을 기반으로 하며, 다음과 같은 주요 기능들을 포함하고 있습니다:

주요 기능

	•	작업 생성 및 관리: 사용자는 작업의 제목, 노트, 날짜, 시작 및 종료 시간, 알림 설정, 반복 주기, 색상 및 완료 상태를 설정하여 작업을 생성할 수 있습니다.
	•	주간 및 월간 반복 설정: 주간 반복은 다음 주의 특정 요일에만 알림을 제공하며, 월간 반복은 매달 특정 날짜에 알림을 제공합니다.
	•	작업 목록 표시: 생성된 작업들은 날짜별로 필터링되어 표시되며, 슬라이더를 통해 작업을 삭제하거나 완료 상태를 업데이트할 수 있습니다.

사용된 패키지

이 프로젝트는 다음 Flutter 패키지들을 사용하여 구현되었습니다:

	•	GetX: 상태 관리 및 의존성 주입을 위한 패키지입니다.
	•	get: ^4.6.6
	•	Get Storage: 간단한 로컬 저장소 솔루션입니다.
	•	get_storage: ^2.1.1
	•	Intl: 날짜 및 시간을 처리하기 위한 패키지입니다.
	•	intl: ^0.19.0
	•	Google Fonts: 구글 폰트를 쉽게 사용하기 위한 패키지입니다.
	•	google_fonts: ^6.2.1
	•	Date Picker Timeline: 날짜 선택을 위한 타임라인 뷰를 제공합니다.
	•	date_picker_timeline: ^1.2.6
	•	Sqflite: SQLite 데이터베이스를 Flutter 애플리케이션에서 사용할 수 있게 해주는 패키지입니다.
	•	sqflite: ^2.3.3+1
	•	Path: 파일 경로 처리를 위한 패키지입니다.
	•	path: ^1.9.0
	•	Flutter Staggered Animations: 리스트 뷰에서 애니메이션 효과를 제공합니다.
	•	flutter_staggered_animations: ^1.1.1
