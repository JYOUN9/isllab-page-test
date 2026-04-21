---
title: Contact
date: 2024-01-01
type: landing

design:
  spacing: "6rem"

sections:
  - block: markdown
    id: notice
    content:
      title: Notice
      text: |
        <style>
          #notice .max-w-prose {
            max-width: min(900px, 90vw) !important;
            width: 100% !important;
          }
          #notice .prose {
            font-size: 0.98rem !important;
            line-height: 1.72 !important;
          }
        </style>
        ISL Lab과 함께할 열정적이고 성실한 연구 학생(석/박사과정, 학부 인턴)을 기다립니다. 멀티모달 학습과 피지컬 AI(Physical AI) 연구에 흥미가 있다면 편하게 지원해 주세요. 하단의 Apply 버튼을 눌러 Google Form으로 지원할 수 있으며, 관심 연구 주제와 함께 CV 및 성적표를 첨부해 주세요.

        The ISL Lab is currently recruiting passionate and diligent research students (MS/PhD programs and undergraduate interns). If you are interested in Multimodal Learning and Physical AI, please feel free to apply. Click the Apply button below to access the Google Form, and please include your research interests, CV, and academic transcript.

        <div class="mt-10 flex flex-wrap justify-center gap-3">
          <a href="https://docs.google.com/forms/d/e/1FAIpQLScYQf-lwtDU-QAPXjflb9WH-COt_b2Xl5a8rkQEoPiPzWjOdA/viewform?usp=header" class="inline-flex items-center justify-center rounded-lg px-4 py-2 text-sm font-semibold text-white no-underline bg-blue-600 hover:bg-blue-700">
            Join us 🚀
          </a>
          <a href="https://sites.google.com/d/1OsnbeneXXVR6Sh1ZF2xAkoAFeU1SKLaX/p/1JGiwAc202JVU9GN-GqaBFi5UP56u1AO_/edit" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center rounded-lg px-4 py-2 text-sm font-semibold text-blue-600 no-underline bg-white border border-blue-600 hover:bg-blue-50">
            Calendar 📅
          </a>
        </div>
    design:
      spacing:
        padding: ["4.25rem", 0, "2rem", 0]

  - block: markdown
    id: resources
    content:
      title: Resources
      text: |
        <div class="resource-copy">
          <p class="resource-copy-lead">
            Individual research equipment is provided as follows:
          </p>
          <ul class="resource-copy-list list-disc pl-6 mt-1 mb-1">
            <li><strong>Graduate Students:</strong> Dedicated workstation comprising a choice of desktop or laptop, complemented by dual monitors.</li>
            <li><strong>Undergraduate Students:</strong> Dual monitor setup provided for individual workspaces.</li>
          </ul>
        </div>
        {{< resource-cards >}}
    design:
      spacing:
        padding: ["2rem", 0, "2rem", 0]
      css_class: "bg-white dark:bg-gray-800"

  - block: markdown
    id: contact-info
    content:
      title: Contact Information
      text: |
        {{< contact-info-cards >}}
    design:
      spacing:
        padding: ["2rem", 0, "2rem", 0]

  - block: markdown
    id: location
    content:
      title: Location
      text: |
        <style>
          #location .max-w-prose,
          #location .prose {
            max-width: min(1260px, 96vw) !important;
            width: 100% !important;
          }

          #location .location-map-box {
            width: 100%;
            height: 460px;
            border: 1px solid rgba(59, 130, 246, 0.24);
            border-radius: 0.8rem;
            overflow: hidden;
            background: #e2e8f0;
            box-shadow: 0 12px 28px rgba(15, 23, 42, 0.08);
          }

          .dark #location .location-map-box {
            border-color: rgba(96, 165, 250, 0.34);
            background: #1f2937;
            box-shadow: 0 14px 32px rgba(2, 6, 23, 0.35);
          }
        </style>
        <div class="location-map-box">
          <iframe
            src="https://www.google.com/maps?q=35.70631,128.4540&hl=ko&z=15&output=embed"
            width="100%"
            height="100%"
            style="border:0;"
            allowfullscreen=""
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade">
          </iframe>
        </div>
    design:
      spacing:
        padding: ["2rem", 0, "2rem", 0]
      css_class: "bg-white dark:bg-gray-800"
      container: false

---
