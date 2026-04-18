# 디자인 시스템 (DESIGN.md)

이 문서는 케이블타이 웹사이트의 디자인 규칙을 정의합니다.

## 1. Typography
- **Primary Font**: `Inter`, `Pretendard`, sans-serif
- **Headings**: Bold (700) ~ ExtraBold (800)
- **Body**: Regular (400) ~ Medium (500)

## 2. Color Palette (Dark Theme)
- **Background**: `#0a0d14` (Deep Industrial Dark)
- **Surface**: `#151b29` (Slightly lighter for cards)
- **Primary (Accent)**: `#FFB800` (Safety/Construction Yellow - 신뢰와 산업의 상징)
- **Secondary**: `#3B82F6` (Electric Blue - 첨단, 신뢰)
- **Text Primary**: `#FFFFFF`
- **Text Secondary**: `#94A3B8`

## 3. Visual Language
- **Glassmorphism**: 반투명 표면과 미세한 테두리(`border: 1px solid rgba(255,255,255,0.1)`)를 사용하여 현대적이고 세련된 느낌을 강조합니다.
- **Micro-animations**: 강력한 결속력을 상징하듯, 요소를 클릭하거나 호버할 때 단단하고 찰진(snappy) 트랜지션 적용 (`transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);`).
- **Gradients**: 백그라운드에 은은하게 푸른빛/노란빛 그라데이션을 깔아 공간감을 형성합니다.

## 6. Design System Notes for Stitch Generation
**(Stitch Loop 프롬프트에 복사할 것)**
- Color Mode: DARK
- Theme: Industrial Premium / Glassmorphism
- Font: Inter / Pretendard
- Primary Color: #FFB800
- Background: #0a0d14
- Styling: Rounded corners (12px), Subtle glow effects for CTAs, High contrast typography.
