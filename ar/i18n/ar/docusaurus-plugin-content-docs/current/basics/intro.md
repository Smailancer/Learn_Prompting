---
sidebar_position: 0
---

# 🟢 مقدمة

import Techniques from '@site/docs/assets/techniques.svg';

<div style={{textAlign: 'center'}}>
  <Techniques style={{width:"100%",height:"300px",verticalAlign:"top"}}/>
</div>

يقدم هذا الفصل تقنيات توجيه بسيطة و مصطلحات. من أجل فهم هندسة الأوامر، تحتاج أولا إلى فهم بعض *مفاهيم الذكاء الاصطناعي الأساسية*. إذا كنت تعرف بالفعل عن المواضيع التالية، لا تتردد في التخطي إلى [المقال التالي](https://learnprompting.org/docs/basics/prompting).

## ما هو الذكاء الاصطناعي؟

من أجل أهدافنا، الذكاء الاصطناعي (AI) هو مجال قام فيه الناس بإنشاء خوارزميات "ذكية" و التي "تفكر" مثل البشر[^1]. يمكن لهذه الخوارزميات كتابة **مقالات**، حل **مشاكل رياضيات**، وإنشاء **الفن**. أحدث التطورات في هذا المجال أنشأت مؤسسات ذكاء اصطناعي متقدمة جدا بحيث يمكنها كتابة **رسائل مبيعات مقنعة**، **مقالات إخبارية**، وحتى **الفوز [مسابقات الفن](https://impakter.com/art-made-by-ai-wins-fine-arts-competition/)**.

يقوم الذكاء الاصطناعي حاليا بإحداث ثورة في العديد من الصناعات، بما في ذلك **الصحافة**، **الرعاية الصحية**و **التعليم**. من المحتمل أن ترى تطبيقاته في مكان العمل/الفصل الدراسي الخاص بك قريباً إذا لم يكن قد حدث بالفعل. وعلى الرغم من أن الذكاء الاصطناعي مفيد للغاية، فإنه يتطلب من البشر أن يوجهوه نحو ما ينبغي أن يفعل. غالباً ما يكون الـ AI ذكياً جداً في الخامسة من العمر. يمكنه فعل الكثير من الأشياء، لكنه يحتاج إلى تعليمات دقيقة للقيام بها بشكل جيد.

القدرة على توجيه االذكاء الاصطناعي بشكل سليم هي مهارة قوية جداً. إذاً، كيف يمكنك التواصل معه؟ يناقش الدرس الخاص بالذكاء الاصطناعي في هذه الدورة فهم اللغة الإنجليزية (وغيرها من اللغات)، حتى يمكننا عادة فقط وصف المهام التي نريد القيام بها. على سبيل المثال يمكننا أن نخبر الذكاء الاصطناعي بـ `كتابة مقالة عن فوائد الذكاء الاصطناعي` وسوف يقول[^2]:

```
في السنوات الأخيرة، أصبح الذكاء الاصطناعي موضوعا ساخنا في عالم التكنولوجيا. ومع إمكانية إحداث ثورة في العديد من جوانب حياتنا، أصبح الذكاء الاصطناعي ذو أهمية متزايدة مع استمرار تطور التكنولوجيا. من تطبيقاته في مجال الرعاية الصحية والنقل إلى استخدامه في التعليم والتصنيع، لقد بين لنا الذكاء الاصطناعي بالفعل إمكانياته الهائلة في إفادة المجتمع بطرق متعددة.

أكثر فوائد الذكاء الاصطناعي وضوحا هو قدرته على أتمتة المهام الروتينية. يمكن استخدام نظم الذكاء الاصطناعي في التشغيل الآلي للعمليات الواسعة النطاق، مثل تحليل البيانات، خدمة الزبائن، وحتى إنتاج السلع. وهذا يحرر العمل البشري ليركز على مهام معقدة وخلاقة تتطلب المزيد من الذكاء البشري والإبداع. كما يمكن استخدام الذكاء الاصطناعي لتحليل كميات كبيرة من البيانات واتخاذ القرارات في جزء صغير من الوقت الذي يستغرقه الإنسان. يمكن أن يكون هذا مفيداً في صناعات مثل المالية، حيث يستطيع الذكاء الاصطناعي اكتشاف الأنماط في سوق الاوراق المالية وتقديم رؤى لم تكن لتكون ملحوظة لولا ذلك.

كما يمكن استخدام الذكاء الاصطناعي في وضع التنبؤات وتوليد الرؤى التي يمكن استخدامها لتحسين الكفاءة والدقة. فعلى سبيل المثال، يمكن استخدام الذكاء الاصطناعي للتنبؤ باتجاهات العملاء وتفضيلاتهم، مما يساعد الأعمال التجارية على اتخاذ قرارات أفضل وزيادة الأرباح. كما يمكن استخدام الذكاء الاصطناعي لتحديد المخاطر والفرص المحتملة في مختلف الصناعات، مثل المالية ،الرعاية الصحية والصناعات التحويلية. ومن شأن كل هذا أن يساعد الشركات على اتخاذ قرارات مستنيرة والحد من مخاطر الأخطاء الباهظة التكلفة.

وأخيرا، يمكن استخدام الذكاء الاصطناعي لتحسين فهمنا للعالم. يمكن استخدام الذكاء الاصطناعي لتحليل مجموعات بيانات كبيرة وتوليد رؤى يمكن استخدامها لفهم العالم من حولنا بشكل أفضل. يمكن استخدام هذا لمساعدتنا في فهم أفضل لآثار تغير المناخ، • تطوير علاجات جديدة للأمراض ، بل والتنبؤ بأحداث مثل الزلازل والفيضانات.

بوجه عام، فإن للذكاء الاصطناعي القدرة على إحداث ثورة في العديد من جوانب حياتنا. من أتمته المهام العادية إلى توليد الرؤى والتنبؤات، يمكن استخدام الذكاء الاصطناعي لتحسين الكفاءة والدقة وفهمنا للعالم. مع استمرار تطور التكنولوجيا، ستزداد أهمية الذكاء الاصطناعي وستزداد قدرته على إفادة المجتمع.
```

## لماذا يجب علي أن أهتم؟

يمكن استخدام الذكاء الاصطناعي لأتمتة المهام التي تقضي ساعات لا تحصى للقيام بها *حاليا*. We mentioned several examples above, but you can also consider any slightly repetitive task you do. It could be writing emails, writing reports, or even writing code. If you can describe the task to an AI, it can likely either do it for you or at least give you a starting point.

## How do I get started?

Read the rest of this chapter, then check out other chapters that interest you. In particular, the [applied prompting](https://learnprompting.org/docs/applied_prompting/overview) section may be of interest if you would like to see how professionals use AI to automate their work. You can experiment with AIs using resources like [Playground](https://beta.openai.com/playground), [other IDEs](https://learnprompting.org/docs/tooling/IDEs/intro), or simply using the interactive [embeds](https://learnprompting.org/docs/basics/intro#embeds) that you will see throughout this site.

Before reading the next article, it is important to note that you don't need any technical background to do prompt engineering. Most of it is trial and error, and you can learn as you go.

### Embeds

This course offers an interactive learning experience. You can experiment with exercises discussed in the course using [embeds](https://embed.learnprompting.org/) that are placed throughout the site.

Here is an **image** of what an embed looks like:

import dyno from '@site/docs/assets/basics/dyno_example.png';
import key from '@site/docs/assets/API_key.png';

<div style={{textAlign: 'center'}}>
  <img src={dyno} style={{width: "750px"}} />
</div>

You should be able to see an embed that looks exactly like this image right below this paragraph. If you can't, you may need to enable JavaScript or use a different browser.

<hr />
Embed here: <iframe
    src="https://embed.learnprompting.org/embed?config=eyJ0b3BQIjowLCJ0ZW1wZXJhdHVyZSI6MCwibWF4VG9rZW5zIjoyNTYsIm91dHB1dCI6IkNob2NvbGF0ZSwgVmFuaWxsYSwgU3RyYXdiZXJyeSwgTWludCBDaGlwLCBSb2NreSBSb2FkLCBDb29raWUgRG91Z2gsIEJ1dHRlciBQZWNhbiwgTmVhcG9saXRhbiwgQ29mZmVlLCBDb2NvbnV0IiwicHJvbXB0IjoiR2VuZXJhdGUgYSBjb21tYSBzZXBhcmF0ZWQgbGlzdCBvZiAxMCBpY2UgY3JlYW0gZmxhdm9yczoiLCJtb2RlbCI6InRleHQtZGF2aW5jaS0wMDMifQ%3D%3D"
    style={{width:"100%", height:"280px", border:"0", borderRadius:"4px", overflow:"hidden"}}
    sandbox="allow-forms allow-modals allow-popups allow-presentation allow-same-origin allow-scripts"
></iframe>
<hr />

Assuming that you can see it, click on the **Generate** button. If this is your first time using it (or you are in a new browser/have cleared cookies), it will ask you to input an [OpenAI API key](https://platform.openai.com/account/api-keys). You can get a free key by clicking [this link](https://platform.openai.com/account/api-keys) and signing up for an OpenAI account. This key allows you to use OpenAI's AIs to generate text in the embeds.

:::note
Although OpenAI provides free credits, you will eventually have to pay to use their AI. Fortunately, it is [relatively cheap](https://openai.com/pricing)!
:::

When you navigate to the [OpenAI API key](https://platform.openai.com/account/api-keys) page, click the **Create new secret key** button. It will pop up a modal that contains a string of text like this:

<div style={{textAlign: 'center'}}>
  <img src={key} style={{width: "750px"}} />
</div>

Put this key into the embed and hit **Save**. You should now be able to use the embeds throughout this site.

Now you have all of the information that you need to get started. Happy Learning!


[^1]: Technically, they are not "thinking" like humans, but this is a simple way to explain it.
[^2]: An AI (GPT-3 davinci-003) did in fact write this.
