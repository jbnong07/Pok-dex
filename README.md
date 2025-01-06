# Poke Book
랜덤한 포켓몬을 뽑아 정보를 볼 수 있는 포켓몬 도감


## 프로젝트 과정에서 배운 것
- CoreDataStack을 구성하는 요소
  - Model / Context / Store Coordinator
  - core data stack을 이용하여 crud를 만들고 싱글톤 패턴을 통해 전역적으로 코어데이터의 작업을 수행하는 법
  - 1:n 관계를 만들어 트레이너별 포켓몬을 설정하는 법
- URLSession을 통해 JSON파일을 받아오고 디코딩 하여 사용하는 기초적인 방법
- ViewController의 생명주기 흐름, isViewAppearing의 등장 배경과 특징
- RXSwift를 이용한 MVVM 구조
- Collection View의 Compositional layout
## 과제 목표
#### Lv1. 
- [X] NetworkManager 구현

#### Lv2. 
- [x] MVVM - Model 구현

#### Lv3. 
- [x] MVVM -  MainViewModel 구현

#### Lv4. 
- [x] MVVM -  MainViewController 구현

#### Lv5. 
- [x] CollectionViewCell 을 클릭했을 때 화면 전환

#### Lv6.
- [x] MVVM -  DetailViewModel 구현

#### Lv7. 
- [x] MVVM -  DetailViewController 구현

#### Lv8. 데이터 업데이트 
- [x]  무한 스크롤 구현


## 커밋 컨벤션
### 깃모지 및 태그 정의
| **깃모지**  | **태그**      | **사용 목적**           | **예시**                         |
|-------------|---------------|-------------------------|----------------------------------|
| 🎉 `:tada:` | `[Init]`      | 프로젝트 초기화         | `🎉[Init]InitialCommit`          |
| ✨ `:sparkles:` | `[Feature]` | 새로운 기능 추가        | `✨[Feature]AddLoginAPI`         |
| 🐛 `:bug:`  | `[Fix]`       | 버그 수정               | `🐛[Fix]ResolveLoginError`       |
| ♻️ `:recycle:` | `[Refactor]` | 코드 리팩토링           | `♻️[Refactor]SimplifyLogic`      |
| 🔥 `:fire:` | `[Remove]`    | 코드/파일 삭제          | `🔥[Remove]DeleteUnusedFile`     |
| 📝 `:memo:` | `[Docs]`      | 문서 추가/수정          | `📝[Docs]UpdateREADME`           |

### 커밋 메시지 구조
1. **커밋 타이틀**
   - **형식**: `<깃모지>[태그]작업내용`
   - 깃모지와 태그를 포함한 요약.
   - 예: `✨[Feature]AddUserRegistration`
3. **커밋 본문 (선택 사항)**  
   - 필요한 경우 작업의 자세한 설명을 추가.
   - 예:
     ```
     ✨[Feature]AddUserRegistration
     - Implement user registration API
     - Add form validation
     ```

## 사용 규칙
1. **깃모지와 태그를 항상 포함**: 작업의 목적을 명확히 하기 위함.
2. **한 커밋, 한 가지 작업**: 변경 사항을 명확히 구분.
