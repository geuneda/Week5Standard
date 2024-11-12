# Week5_Standard
 
## 1. 전략패턴을 활용한 다양한 원거리 무기 공격 패턴 구현

### Assets\Scripts\Item\WeaponStrategy


### 1. 직선으로 진행하는 총알
#### (GunStrategy.cs)

### 2. 포물선을 그리며 움직이는 투척물
#### (BowStrategy.cs)

### 3. 원 모양으로 퍼져나가는 마법 공격
#### (MagicStrategy.cs)

### 4. 동적 적용 예제
#### Assets\Scripts\Item\Equip.cs

## 2. 플레이어가 2개 이상의 스킬을 사용할 수 있고, 해당 스킬을 퀵슬롯에 등록할 수 있다고 할 때, 어떻게 구현해야 할까요?

### 명령패턴과 전략패턴을 함께 사용하여, 구현하는것이 좋아보입니다.


#### 1. 전략패턴을 이용하여 스킬을 개별 클래스로 구현합니다. 이렇게 하면 추후 새로운 스킬을 추가할 때 인터페이스만 구현하면 쉽게 사용할 수 있습니다.

#### 2. 위에서 구현한 인터페이스를 퀵슬롯에 등록하고 실행할 수 있는 명령으로 만듭니다. 이렇게 하면 스킬을 쉽게 추가 및 변경할 수 있습니다.
