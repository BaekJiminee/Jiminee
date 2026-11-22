# 포켓몬 영문 도감 설명의 텍스트 마이닝: 타입 예측과 세대별 문체 변화
영어데이터처리를위한프로그래밍(2) 미니 프로젝트

## 프로젝트 소개
포켓몬 영문 도감 설명(Pokédex entry)을 수집해 두 가지를 분석했습니다.
- **RQ1.** 도감 설명의 어휘만으로 포켓몬의 타입(Type1)을 얼마나 맞힐 수 있는가?
- **RQ2.** 도감 설명의 문체(길이, 품사 비율)는 게임 세대에 따라 달라지는가?

## 파일 설명
| 파일 | 내용 |
|---|---|
| `pokemon_pokedex_mining.ipynb` | 전체 코드 (수집 → 전처리 → 분석 → 시각화) |
| `pokemon.csv` | 종별 번호, 이름, 타입, 능력치 |
| `pokemon_entries_raw.csv` | 수집한 도감 설명 원본 |
| `pokemon_corpus.csv` | 전처리를 마친 도감 설명 |
| `keyword_by_type.png` | 타입별 핵심 키워드 |
| `type_confusion.png` | 타입 예측 혼동행렬 |
| `style_by_generation.png` | 세대별 문체 비교 |