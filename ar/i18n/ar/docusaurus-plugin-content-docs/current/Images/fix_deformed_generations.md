---
sidebar_position: 9p
---

# 🟢 إصلاح الأجيال المشكّلة

والأجيال المشوهة، ولا سيما على أجزاء الجسم البشري (مثل اليدين والأقدام)، هي مسألة مشتركة مع نماذج كثيرة. ويمكن معالجة هذا الأمر إلى حد ما بأمر سلبي جيد (@blake2022with). المثال التالي تم تكييفه من [هذه المشاركة في Reddit](https://www.reddit.com/r/StableDiffusion/comments/z7salo/with_the_right_prompt_stable_diffusion_20_can_do/).

## مثال

استيراد good_pitt من '@site/docs/assets/images_chapter/good_pitt.png'; استيراد bad_pitt من '@site/docs/assets/images_chapter/bad_pitt.png';

باستخدام التنفيس المستقر v1.5 والموجة التالية، نحن نولد صورة جميلة لبراد بيت، باستثناء يديه في الدورة التدريبية!

`صورة استوديو متوسطة لبراد بيت تلوح بيديه، فيلم مفصل، إضاءة استوديو، عدسة 90 مم، من قبل مارتن شويلر(6)`

<div style={{textAlign: 'center'}}>
  <img src={bad_pitt} style={{width: "250px"}} />
</div>

Using a robust negative prompt, we can generate much more convincing hands.

``
<div style={{textAlign: 'center'}}>
  <img src= style={{width: "250px"}} />
</div>

Using a similar negative prompt can help with other body parts as well. Unfortunately, this technique is not consistent, so you may need to attempt multiple generations before getting a good result. In the future, this type of prompting should be unnecessary since models will improve. However, currently it is a very useful technique.


# Notes

Improved models such as [Protogen](https://civitai.com/models/3666/protogen-x34-official-release) are often better with hands, feet, etc.