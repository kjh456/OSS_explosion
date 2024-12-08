# OSS 저작권 안내

오픈 소스 소프트웨어(OSS)의 저작권은 소프트웨어의 사용, 수정, 배포 조건을 정의하며, OSS 라이선스를 통해 구체화됩니다. 이는 소프트웨어를 공개적으로 제공하면서도 저작권자의 권리를 보호하고, 사용자에게 소스 코드를 활용할 수 있는 권한을 명확히 전달합니다.

---

## 📜 주요 개념

### 1. **저작권 보호**
- 오픈 소스 소프트웨어도 기본적으로 저작권법의 보호를 받습니다.
- OSS는 사용 권한을 부여하지만, 저작권자는 특정 조건을 설정할 수 있습니다.

### 2. **라이선스를 통한 조건 부여**
OSS 저작권자는 **오픈 소스 라이선스**를 통해 사용, 수정, 배포 등의 조건을 명시합니다.  
대표적인 OSS 라이선스는 다음과 같습니다.

- **MIT License**: 매우 자유로우며, 거의 모든 용도로 사용 가능.
- **GNU GPL (General Public License)**: 수정 및 배포 시 소스 코드를 공개해야 함.
- **Apache License 2.0**: 특허 보장을 포함한 조건을 명시.
- **BSD License**: 간결한 조건으로 제한 없이 사용 가능.

### 3. **저작권 표시**
대부분의 OSS 라이선스는 소스 코드에 저작권 표시와 라이선스 사본을 포함하도록 요구합니다.  
예: `Copyright (c) 2024, csb0597`

### 4. **사용자의 권리**
OSS는 소프트웨어 사용, 수정, 배포를 허용하며, 일부 라이선스는 상업적 사용까지 허용합니다.  
단, 사용자가 소스 코드를 수정하거나 재배포할 경우 원 저작자를 명시해야 할 수도 있습니다.

---

## ⚖️ 자주 언급되는 개념

### **Copyleft**
- 소스 코드를 수정하거나 확장한 후 이를 배포할 경우, **수정된 코드도 동일한 라이선스 조건을 따라야** 한다는 개념.
- GNU GPL이 대표적인 Copyleft 라이선스입니다.

### **Permissive License**
- 사용자가 코드를 수정, 배포, 상업적으로 이용할 수 있는 권한을 자유롭게 제공.
- 예: MIT, Apache, BSD 라이선스.

### **특허 보장 (Patent Grant)**
- 일부 OSS 라이선스는 사용자가 소프트웨어와 관련된 특허 침해로부터 보호받을 수 있도록 보장합니다.
- Apache License 2.0이 이에 해당합니다.

### **Dual Licensing**
- 소프트웨어를 두 개 이상의 라이선스로 제공하여 사용자 선택의 폭을 넓히는 방식.
- 예: 하나는 상업적 사용, 다른 하나는 오픈 소스 사용을 위한 라이선스.

---

## 🚦 OSS 저작권 준수 방법

### 1. **라이선스 조건 준수**
- 소프트웨어 사용 전에 해당 소프트웨어의 라이선스를 반드시 확인하세요.
- 수정 및 배포 시 요구 사항(저작권 표시, 라이선스 사본 포함 등)을 충족해야 합니다.

### 2. **저작권 및 저작자 표시 유지**
- 대부분의 OSS는 원 저작자의 이름과 저작권 표시를 유지해야 합니다.

### 3. **서드파티 라이브러리 사용 확인**
- 프로젝트에서 사용하는 외부 라이브러리도 각자의 OSS 라이선스를 따르므로, 이를 검토해야 합니다.

### 4. **소스 코드 공개 요건 확인**
- Copyleft 라이선스를 따르는 경우, 수정된 코드를 공개해야 할 수 있습니다.

---

## 🚨 OSS 라이선스 위반 시

OSS 라이선스는 법적 효력을 가지므로, 이를 위반하면 저작권 침해에 해당할 수 있습니다.

### **위반 사례**
- 수정한 소스 코드를 공개하지 않음 (GPL 위반).
- 저작권 표시를 제거하거나 변경함.

### **위반 결과**
- 법적 소송 또는 사용권 취소.

---

## 🌟 OSS 저작권의 중요성

1. **저작자의 권리 보호**  
   공개된 소프트웨어라 하더라도 저작권자의 기여를 인정하고 보호합니다.

2. **사용자의 신뢰 제공**  
   OSS 라이선스를 통해 사용자는 소프트웨어의 사용 범위와 제한을 명확히 알 수 있습니다.

3. **개발 생태계 지원**  
   OSS는 개발자들이 지식을 공유하고 협력할 수 있는 환경을 조성하며, 저작권을 통해 지속 가능한 오픈 소스 생태계를 유지합니다.

---

## 📝 라이선스 종류

### 1. **Copyleft 라이선스**
- **GPL (General Public License)**:
  - 소스 코드를 수정하여 배포할 경우, 수정된 소스 코드도 GPL 라이선스 하에 배포해야 합니다.
  - 또한, 소스 코드 공개가 의무화됩니다. 예를 들어, `GNU GPL v3`는 소스 코드가 상용 소프트웨어에 포함될 경우 그 소프트웨어의 소스 코드도 공개해야 합니다.
  - **예시**: GNU 프로젝트의 소프트웨어, 리눅스 커널.

- **AGPL (Affero General Public License)**:
  - AGPL은 GPL의 개정판으로, 웹 애플리케이션과 같이 네트워크 상에서 소스 코드 변경 내용을 제공해야 하는 경우에 적용됩니다.
  - 예를 들어, 웹 서버에서 소프트웨어를 실행할 때 사용자가 소스 코드를 변경한 경우, 그 변경 사항도 공개해야 합니다.

### 2. **Permissive 라이선스**
- **MIT License**:
  - 가장 자유로운 라이선스 중 하나로, 소프트웨어를 사용, 수정, 배포, 상업적 목적을 위해 사용할 수 있습니다.
  - 단, 저작권 표시와 라이선스 사본을 포함시켜야 합니다.
  - **예시**: 대부분의 자바스크립트 라이브러리, Node.js.

- **Apache License 2.0**:
  - MIT보다 조금 더 복잡한 조건을 가지고 있지만, 특허 관련 문제를 해결해주는 장점이 있습니다. 이 라이선스는 특허를 제공하며, 그 소프트웨어를 사용해도 특허 침해를 걱정할 필요가 없습니다.
  - 또한, 수정된 코드에 대해 별도의 저작권 표시를 요구합니다.
  - **예시**: Apache Software Foundation의 프로젝트들, 예: Hadoop, Kafka.

- **BSD License**:
  - MIT와 비슷하지만, BSD는 원래 대학에서 시작된 라이선스로, 특별한 조건 없이 상업적 사용과 배포가 가능합니다.
  - **예시**: FreeBSD, OpenBSD.

### 3. **혼합형 라이선스**
- **Creative Commons (CC)**:
  - 오픈 소스와 관련된 라이선스라기보다는 콘텐츠 라이선스에 많이 사용되지만, 오픈 소스 프로젝트에도 사용될 수 있습니다.
  - CC 라이선스는 특정 조건 하에 콘텐츠(이미지, 글 등)를 재사용하거나 수정하는 것을 허용합니다. 
  - **예시**: 위키백과, 일부 문서 및 콘텐츠.

---

## 🔧 라이선스 파일 구성
프로젝트의 라이선스는 보통 `LICENSE`라는 이름으로 프로젝트 루트 디렉토리에 위치하게 됩니다. 이 파일에는 사용자가 프로젝트를 어떻게 사용할 수 있는지, 라이선스가 적용되는 범위와 조건을 명시합니다.

라이선스 파일에 포함되는 항목은 대개 다음과 같습니다.
- **라이선스 이름**: 예를 들어, MIT, GPL 3.0, Apache 2.0.
- **저작권자**: 소프트웨어를 개발한 저작권자의 이름.
- **저작권 연도**: 소프트웨어가 작성된 연도.
- **라이선스 조건**: 사용자가 소프트웨어를 어떻게 사용할 수 있는지, 어떤 제한이 있는지.

#### 예시 (MIT License)

MIT License

Copyright (c) 2024 csb0597

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

## 🌍 OSS 상용화 및 기업 사용
OSS 라이선스를 준수하면 소프트웨어를 상용화할 수 있습니다. 그러나 OSS를 사용할 때 상용화에 영향을 미칠 수 있는 몇 가지 사항이 있습니다.

- **GPL의 경우**: 소스 코드를 수정하거나 배포할 때 수정된 소스 코드를 공개해야 합니다. 이는 상용화 시 공개된 소스 코드를 포함할 수 있어, 많은 기업들이 GPL 라이선스를 피하려고 합니다.
- **MIT/Apache/BSD 라이선스의 경우**: 이러한 라이선스는 상업적 사용을 허용하므로, 기업들은 이를 선호합니다. 사용자는 수정한 코드나 소프트웨어를 상업적으로 사용할 수 있습니다.

---

## 📌 OSS 커뮤니티 협력

OSS는 대개 커뮤니티 기반으로 발전합니다. 프로젝트의 저작권을 관리하고 보호하면서도 커뮤니티와 협력할 수 있는 방식으로 진행되는 경우가 많습니다. 예를 들어, 다음과 같은 사항들이 중요합니다.

- **포크(fork)**: 사용자가 원본 소스코드를 복사하여 자신만의 프로젝트를 만들고, 이를 개선한 후 다시 커뮤니티에 기여할 수 있습니다.
- **풀 리퀘스트(Pull Request)**: 코드 변경을 제안하는 방식으로, 다른 사람의 프로젝트에 기여하거나 수정 사항을 추가할 수 있습니다.
- **기여 가이드라인**: 프로젝트에 기여할 때 따라야 할 규칙을 설정하여, 모든 기여자가 동일한 기준을 따를 수 있도록 합니다.

---

## 🔧 라이선스 선택 도구
다양한 OSS 라이선스를 선택할 때 참고할 수 있는 도구들이 있습니다. 예를 들어

- [ChooseALicense.com](https://choosealicense.com/): 라이선스 선택에 도움이 되는 도구입니다. 질문을 통해 프로젝트에 가장 적합한 라이선스를 추천해줍니다.
- [Open Source Initiative](https://opensource.org/licenses): 다양한 오픈 소스 라이선스를 소개하고, 각 라이선스의 특징과 적용 범위를 설명합니다.

---

이 정보를 README에 추가하면, 프로젝트에 대한 라이선스와 저작권 정보를 명확히 전달할 수 있습니다.
