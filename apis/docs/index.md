# Backstage POC 가이드

## 1. 개요
### *[Backstage 공식 문서 링크](https://backstage.io/docs/overview/what-is-backstage)*
- **목적: Backstage를 내부 개발 포털로 도입하기 위한 가능성 검토 및 POC 진행.**
- **범위: 카탈로그 통합, 템플릿 생성 자동화, Azure 인증 및 RBAC(Role-Based Access Control) 기능 포함.**
  
<br>

## 2. 프로젝트 개요
- 소속: ktds 플랫폼사업본부 플랫폼CoE팀
- 담당자:
  - 주성환 과장
  - 여정동 사원
  
<br>

## 3. POC 주요 기능
#### 1. 카탈로그 통합
  - 프로젝트 정보 카탈로그 등록
  - GitHub 레포지토리와의 통합

#### 2. 소프트웨어 템플릿 생성
  - 마이크로서비스 및 GitHub Actions 템플릿 자동 생성.
  - Custom Template Actoin 개발 및 적용 

#### 3. Github 및 Azure 인증
  - Backstage 사용자 Azure 로그인 또는 Github 인증 사용 가능하도록 연동

#### 4. Azure RBAC 기반 커스텀 접근 권한 정책 적용
  - Custom Permission 적용
  - 현재 Owner 역할 사용자만 템플릿 생성 가능하도록 설정.

#### 5. TechDoc 적용
  - Docker로 자동 빌드 및 생성되는 TechDoc 적용

<br>

## 4. 세부 적용 가이드
#### [1. Backstage Catalog 등록 가이드](./pages/catalog-guide.md)
#### [2. Backstage Software Template (yml 파일) 작성 가이드](./pages/template-guide.md)
#### [3. Backstage Software Custom Action code 작성 가이드](./pages/custom-action-guide.md)
#### [4. Backstage Custom Permission 개발 및 적용 가이드](./pages/custom-permission-guide.md)
#### [5. Backstage Custom Plugin 개발 및 적용 가이드](./pages/custom-plugin-guide.md)
<br>

