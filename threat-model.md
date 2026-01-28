# Threat Model

bigvirtue1 targets threat models that traditional encryption tools like VeraCrypt cannot fully address.

Key Points:
- **Hardware-bound security**: Encryption keys are tied to specific devices or physical security tokens.
- **Zero-trace principle**: Data is immediately wiped from memory and disk after access.
- **Developer-sovereign control**: The user holds full authority over the system; external verification is not assumed.
- **Controlled backup option**: Users can choose to enable secure recovery on other authorized devices.

This model is intended for environments where data leakage is considered far worse than loss of access.

# 위협 모델

bigvirtue1은 VeraCrypt와 같은 전통적 암호화 도구가 완전히 다루지 못하는 위협 모델을 목표로 합니다.

핵심 포인트:
- **하드웨어 바인딩 보안**: 암호화 키는 특정 장치나 물리적 보안키에 묶입니다.
- **제로 트레이스 원칙**: 데이터는 접근 후 메모리와 디스크에서 즉시 삭제됩니다.
- **개발자 주권형 제어**: 사용자가 시스템을 완전히 통제하며, 외부 검증은 전제로 하지 않습니다.
- **선택적 안전 복구**: 사용자가 허용한 경우에만 다른 장치에서 복구가 가능합니다.

이 모델은 데이터 유출이 접근 손실보다 훨씬 큰 환경을 위해 설계되었습니다.
