# Interview 대비 
안드로이드 개발자로서 알아야 할 개념들에 대해 정리하는 레포입니다.
<br/>
## 파일 및 레포지토리 설명
- [URL.md](https://github.com/HaeUlNam/Android-Developer-Interview/blob/master/URL.md) : 참고하면 좋을 만한 안드로이드 관련 URL을 정리해두었습니다.
- [PROGRESS.md](https://github.com/HaeUlNam/Android-Developer-Interview/blob/master/PROGRESS.md) : 주차별 진행 정도 및 담당 파트를 기록했습니다.

## OS
- 시스템 콜(유저 모드, 커널 모드)
- 시스템 부트
- 스레드, 프로세스
- Deadlock, Synchronization
- Main memory, Virtual memory
- CPU 스케줄링
- File system (Inode, journaling, allocation, caching ...) 
- Disk 스케줄링(HDD vs SSD)
- IO system(polling, Interrupt, blocking, non blocking)
- ...

## Network
- 우선은 책으로 기본 개념 학습
- Http, Https + REST + 대칭키 비대칭키 
- 5계층
- ... 

## DB
- 트랜잭션, join
- 관계형 DB vs 비관계형 DB 
- Indexing, B+ tree
- ...

## Android
### 어떻게 사용하는지 + 예제 + 문제 발생시에 해결 방안
- 4대 컴포넌트
- Fragment , intent , context
- 핸들러, 루퍼, 메세지 큐 , ui thread , 비동기 라이브러리
- View lifecycle
- Context
- MVC, MVP, MVVM 왜 쓰는가. 각 패턴의 장단점.
- 가능하면 Jetpack
- ...

## Java
- JVM 구조 - > 안드로이드와 연결하여 공부
- GC
- Collection , 람다
- 제너릭
- Class, interface 상속 ( OOP개념. 왜 쓰는지)
- ...

## Design Pattern
- 5대 원칙(SOLID)
- 싱글톤  
- 어댑터
- 빌더
- 위임 패턴
- 데코레이터
- 전략 패턴
- ...

## Algorithm + Data Structure
- BST -> AVL -> RB, B+
- 우선 순위 큐(힙으로 구현)
- 정렬 알고리즘(quick , merge)
- MST(크루스칼, 프림) + disjoint set + union find
- 다익스트라, 밸만포드
- ...