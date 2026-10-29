---
layout: default
title: Privacy Policy
---

# 개인정보처리방침 (Privacy Policy)

**시행일: 2026년 10월 29일**

## 1. 개요

Personal Obsidian Drive Sync는 개인 Obsidian 노트와 Google Drive 사이의 파일 동기화를 위해 설정한 OAuth 애플리케이션입니다.

이 OAuth 클라이언트는 오픈소스 GSync 플러그인을 사용하는 데 필요한 Google API 인증 목적으로 제공됩니다.

## 2. 접근하는 Google 사용자 데이터

Google Drive API를 이용하여 다음 데이터에 접근할 수 있습니다.

- Google Drive 파일 및 폴더의 이름, 경로, 크기, 수정 시각 등 메타데이터
- 동기화 대상 파일의 내용
- 파일의 생성, 수정 및 삭제에 필요한 정보

사용하는 OAuth 권한은 `https://www.googleapis.com/auth/drive`입니다.

이 권한은 기술적으로 Google Drive 전체 파일에 대한 접근을 허용하지만, GSync는 사용자가 지정한 동기화 폴더 안의 파일을 관리하도록 설계되어 있습니다.

## 3. 데이터 이용 목적

Google 사용자 데이터는 다음 목적으로만 이용됩니다.

1. Obsidian과 Google Drive 사이의 양방향 파일 동기화
2. 변경된 파일의 확인 및 업데이트
3. 파일 충돌 감지와 동기화 상태 관리
4. 사용자가 허용한 파일 삭제 사항 반영

Google 사용자 데이터는 광고, 마케팅, 사용자 프로파일링 또는 인공지능 모델 학습에 사용하지 않습니다.

## 4. 데이터 저장 및 전송

GSync의 노트 동기화는 사용자의 기기와 Google Drive API 사이에서 직접 이루어집니다.

OAuth 인증 정보와 갱신 토큰은 사용자의 기기 내 GSync 플러그인 설정 파일에 저장됩니다.

Google Drive의 노트 파일을 별도의 애플리케이션 서버에 수집하거나 보관하지 않습니다.

GitHub Pages는 본 안내 페이지와 개인정보처리방침 게시에 사용되며, Obsidian 노트 내용을 저장하는 용도로 사용되지 않습니다.

## 5. 제3자 제공

Google 사용자 데이터를 광고주, 데이터 브로커 또는 기타 외부 사업자에게 판매하거나 제공하지 않습니다.

데이터 동기화에는 Google Drive API가 사용됩니다. 서비스 이용 과정에서 Google 및 웹 호스팅 사업자에게 적용되는 데이터 처리에는 각 사업자의 정책이 적용됩니다.

## 6. 데이터 보관 및 삭제

동기화된 파일은 사용자의 Google Drive 및 각 기기의 Obsidian Vault에 보관됩니다.

사용자는 자신의 Google Drive 또는 Obsidian에서 파일을 직접 삭제할 수 있습니다. GSync에서 삭제 동기화 기능을 활성화한 경우 삭제 사항이 다른 저장 위치에도 반영될 수 있습니다.

OAuth 접근 권한은 [Google 계정의 서드파티 앱 연결 관리](https://myaccount.google.com/permissions)에서 철회할 수 있습니다.

기기에 저장된 OAuth 인증 정보는 GSync 연결 해제 및 해당 플러그인 데이터 삭제를 통해 제거할 수 있습니다.

Google Drive의 파일 보관 및 휴지통 정책은 Google의 서비스 정책을 따릅니다.

## 7. 데이터 보안

Google 인증에는 OAuth 2.0을 사용하며, Google API와의 통신에는 HTTPS가 사용됩니다.

GSync 플러그인의 동작 방식에 대한 자세한 내용은 [공식 소스 코드](https://github.com/dg0988/ObsidianGSync)에서 확인할 수 있습니다.

사용자는 OAuth 인증 토큰이나 클라이언트 보안 정보를 외부에 공개하지 않아야 합니다.

## 8. Google API 데이터 사용 정책

본 OAuth 애플리케이션을 통해 취득한 Google 사용자 데이터는 Google API Services User Data Policy와 해당 정책의 Limited Use 요건에 부합하는 목적으로만 사용됩니다.

## 9. 개인정보처리방침 변경

데이터 접근 범위 또는 처리 방식이 변경되는 경우 본 문서를 갱신합니다.

## 10. 문의

서비스 명칭: Personal Obsidian Drive Sync

관리자 연락처: [본인 연락처 이메일 입력]
