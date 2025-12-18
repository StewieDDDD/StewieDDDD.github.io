---
layout: post
title: History of Version Control Systems
---

# 버전 관리 시스템의 역사

버전 관리 시스템(VCS, Version Control System)은 소스 코드의 변경 이력을 관리하고, 협업을 가능하게 하는 핵심 도구이다.  
아래는 주요 버전 관리 시스템의 발전 과정을 시간 순서대로 정리한 내용이다.

---

## SCCS (Source Code Control System)
- **1972~1973년**, 벨 연구소(Bell Labs)에서 개발된 **최초의 버전 관리 시스템**
- 파일의 변경 내용을 **델타(delta) 방식**으로 저장

## RCS (Revision Control System)
- **1982년** 등장한 초기 **로컬 버전 관리 시스템**
- 파일 단위로 버전을 관리하며, SCCS보다 단순하고 효율적인 구조

## CVS (Concurrent Versions System)
- **1990년** 발표된 **중앙집중식 버전 관리 시스템**
- RCS의 한계를 극복하고 여러 사용자의 **동시 작업**을 지원

## SVN (Subversion)
- **2000년**, Apache Software Foundation에서 개발
- CVS의 구조적 문제를 개선한 **중앙집중식 버전 관리 시스템**
- 디렉터리 단위 버전 관리, 원자적 커밋(Atomic Commit) 지원

## BitKeeper
- **2000년**, BitMover 사에서 개발한 **분산 버전 관리 시스템**
- 상용(사유) 소프트웨어
- 한때 리눅스 커널 개발에 사용됨

## Mercurial
- **2005년** 발표된 **분산 버전 관리 시스템**
- 단순한 명령어와 높은 성능을 목표로 설계됨

## Git
- **2005년**, Linus Torvalds가 **리눅스 커널 프로젝트**를 위해 개발
- 현재 가장 널리 사용되는 **분산 버전 관리 시스템**
- 빠른 속도, 무결성, 강력한 브랜치 관리가 특징

---

> 중앙집중식 버전 관리 시스템(CVS, SVN)에서  
> 분산 버전 관리 시스템(Git, Mercurial)으로의 전환은  
> 현대 소프트웨어 개발 방식에 큰 변화를 가져왔다.
