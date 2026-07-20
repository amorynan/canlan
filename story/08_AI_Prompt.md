# 08_AI_Prompt.md

# 《灿烂》AI 动画 Prompt v1.0

> 对应：`05_分镜.md`
>
> 用途：Veo / Runway / Pika / Hailuo / 即梦 等文生视频或图生视频工具
>
> 方法：先使用全局风格和角色锁定，再按 Shot 添加镜头 prompt。

---

# 使用方式

每个镜头生成时组合：

```text
GLOBAL_STYLE
+ CHARACTER_LOCK（如涉及人物）
+ SCENE_STYLE（如涉及城市）
+ SHOT_PROMPT
+ NEGATIVE_PROMPT
```

建议：

1. 每个 10 秒以上镜头拆成 2-4 个子镜头。
2. 先为五个阶段分别生成角色参考图，再做视频。
3. 同一个阶段的所有镜头使用同一张角色参考图。
4. 不要让工具自动生成夸张表情，所有情绪保持克制。

---

# GLOBAL_STYLE

```text
2D animated short film, grounded magical realism, quiet slice-of-life atmosphere, soft natural light, realistic Chinese city details, hand-painted backgrounds, delicate linework, subtle facial animation, gentle wind, warm human texture, cinematic composition, slow pacing, minimal dialogue, environmental sound driven storytelling, restrained camera movement, emotional but not melodramatic, inspired by the life observation quality of Japanese animated films and quiet realist cinema, not a fantasy adventure, not sci-fi.
```

---

# NEGATIVE_PROMPT

```text
no photorealistic live action, no 3D plastic look, no glossy game render, no cyberpunk, no sci-fi portal, no time travel visual effects, no magical particles except very subtle dust in light, no exaggerated anime face, no chibi style, no large eyes distortion, no overdramatic crying, no action montage style, no music video fast cuts, no neon gradients, no floating orbs, no bokeh blob background, no text overlays unless specified, no subtitles, no logo watermark.
```

---

# CHARACTER_LOCK

## 红 / 13-15 / 阆中

```text
Character Red: a 13 to 15 year old Chinese student, short and slim, short slightly messy naturally flipped hair, bright curious eyes, lively but not childish, wearing a white school uniform and sneakers, carrying a bulky schoolbag with an English book, gender-neutral presentation, expressive eyes, fast runner, warm red sunset color palette.
```

## 灰 / 16-18 / 绵阳

```text
Character Gray: a 16 to 18 year old Chinese boarding school student, rounder face and heavier body from stress and lack of exercise, slightly hunched shoulders, messy short hair, glasses, tired but persistent eyes, wearing a gray-white high school uniform, carrying heavy books and exercise workbooks, restrained expression, winter gray palette.
```

## 橙 / 18-22 / 西南石油大学

```text
Character Orange: an 18 to 22 year old Chinese university student, slimmer from regular fitness, sharper focused eyes, short practical hair, glasses, simple campus clothes, often carrying a laptop and sports bottle, calm leader energy, absorbed in code and algorithms, warm orange laboratory light palette.
```

## 金 / 22-26 / 北京

```text
Character Gold: a 22 to 26 year old Chinese software engineer in Beijing, strong healthy swimmer body, open posture, broad shoulders, confident warm eyes, short neat hair, simple work clothes, carries swim goggles, coffee and books, energetic but quiet, golden winter sunlight palette.
```

## 蓝 / 27-28 / 成都

```text
Character Blue: a 27 to 28 year old Chinese professional in Chengdu, gained weight compared with Beijing years, quieter posture, slightly tired eyes that still light up when inspired, glasses or occasionally touching the bridge of the nose, simple home clothes or office wear, works on a Mac, coffee, AI animation, renovation papers, calm blue night palette.
```

---

# SCENE_STYLE

## 阆中

```text
Langzhong ancient town in Sichuan, real Chinese old town streets, gray tiled roofs, stone pavement, Jialing River wind, warm red sunset, small breakfast shops, bicycle bells, school commute, soft summer air, lively friends but gentle composition.
```

## 绵阳

```text
Mianyang boarding high school in winter, gray classrooms, dormitory bunk beds, cafeteria steam, hot rice noodles, fluorescent lights, foggy campus roads, heavy exercise books, quiet pressure, restrained symmetrical framing.
```

## 西南石油大学

```text
Southwest Petroleum University campus, warm orange laboratory, laptops, whiteboards, glass walls with algorithm diagrams, gym bag, late-night fluorescent lights, focused coding atmosphere, quiet team energy.
```

## 北京

```text
Beijing Wudaokou in winter, golden morning light, apartment, office with monitors, swimming pool, wood-toned bookstore, coffee shop, clean fast city rhythm, warm mature vitality.
```

## 成都

```text
Chengdu modern apartment and office, blue rainy night, Mac computer, coffee machine, renovation contracts, quiet home lighting, AI animation tools on screen, calm rebuilding mood, warm desk lamp inside cool city weather.
```

## 未知房间

```text
An unknown memory room that feels real, not fantasy: one long wooden table under a warm lamp, five color zones subtly present through objects and light, window curtain moving in a soft wind, ordinary books, laptop, coffee cup, swim goggles, milk note, no sci-fi effects, no portal, no glowing magic, quiet acceptance.
```

---

# SHOT_PROMPTS

## P-S001

```text
Black screen. No image. Five environmental sounds appear one by one: wind over old Chinese roof tiles, boiling rice noodles in a cafeteria, mechanical keyboard in a quiet lab, swimming pool water and breathing, coffee grinder. After the sounds overlap, all stop at once.
```

## P-S002

```text
An English textbook lies on the wooden floor of a small student bedroom. Morning sunlight slowly crawls across the book pages. Red-tinted warm light, curtain moving gently in wind, low fixed camera, quiet and intimate.
```

## P-S003

```text
Character Red rushes barefoot into the bedroom, picks up the English book, hugs it to the chest, opens the window. Outside is Langzhong ancient town with gray roofs, Jialing River air and soft morning light. Low camera following the movement, lively but gentle.
```

## P-S004

```text
Character Gray wakes in a winter boarding school dormitory. Gray light, bunk beds, school broadcast alarm. A hand reaches out from the quilt, finds glasses, puts them on. The student sits up slowly and stares for five seconds. Fixed symmetrical medium shot, quiet pressure.
```

## P-S005

```text
Character Orange wakes up at a university laboratory desk after sleeping beside a laptop. The screen still shows LeetCode Hard Accepted from last night. Orange laboratory light, early morning outside. The character looks at the screen and smiles very slightly. Close fixed shot, screen reflection on glasses.
```

## P-S006

```text
Character Gold in a clean Beijing apartment at 5:30 AM, packing swim goggles, swim cap and swim bag with efficient movements. Golden winter sunlight enters the room and highlights strong swimmer shoulders. Side medium shot with slow lateral camera move.
```

## P-S007

```text
Character Blue sits quietly in a Chengdu apartment. Coffee machine works. A Mac wakes up and shows the date November 18. The home is beautiful but quiet, with renovation traces. Blue looks at the date, then opens work software without expression. Static long shot, cool blue morning.
```

## P-S008

```text
Match cut sequence: five close-ups of hands lifting the first drink of the day. Soy milk in Langzhong, hot rice noodle soup in Mianyang, protein shake in university, black coffee in Beijing, Americano in Chengdu. Each character drinks with the left hand and lightly frowns while thinking. Same framing, same rhythm.
```

## P-S009

```text
Parallel montage of five mornings: Red rides a bicycle through Langzhong ancient streets with an English book in the basket; Gray runs toward a steaming cafeteria; Orange runs into a university lab with a laptop; Gold rides a shared bike with a swim bag in Beijing; Blue opens a Mac while holding coffee as work messages appear. Gentle city awakening, no fast cuts.
```

## P-S010

```text
Langzhong street corner. Character Red rides a bicycle through the ancient town with friends, mixing English and Chinese while joking. A shop owner starts calling a name but the shot cuts before the full name is heard. Fixed street-corner camera, wind lifts an English vocabulary paper.
```

## P-S011

```text
Mianyang high school cafeteria. Character Gray sits in a corner with hot rice noodles. Steam fills the frame. An older sister quietly puts a piece of beef into Gray's bowl. No full frontal face, only hands, chopsticks, soup, steam and a small softened reaction.
```

## P-S012

```text
Warm orange university lab. Character Orange enters, a teammate says the algorithm is broken. Orange sits down, solves the bug in minutes, smiles slightly, taps the teammate's shoulder, returns to own laptop. Camera ends on a small sun doodle sticky note in the corner of the whiteboard.
```

## P-S013

```text
Beijing office. Character Gold stands beside engineers, watches code for twenty seconds, points to one line, the bug disappears after running. Gold walks away with coffee, passes a bookshelf, picks up a book titled Bai Ye Xing with an old-town landscape bookmark. Calm confident motion, golden office light.
```

## P-S014

```text
Chengdu office. Character Blue is surrounded by overlapping work messages, meeting audio, renovation calls, bank calls, property calls. Sound becomes overwhelming, camera slowly pushes in. Suddenly everything mutes. Blue removes glasses, rubs the brow, lightly frowns, drinks coffee, puts glasses back on and continues.
```

## P-S015

```text
Five-problem match cut: Red is asked to read English and raises a hand after a light frown; Gray faces a final math problem and continues; Orange gets Wrong Answer and continues; Gold sees a new online bug and continues; Blue finds a suspicious renovation contract clause and continues. Same angle, same character position, same light frown.
```

## P-S016

```text
Life-force montage: Red and friends on the city wall solving math and laughing; Gray studies during evening self-study while sister waves outside; Orange trains in a gym with sweat and strength; Gold swims, reads in a wooden bookstore, drinks coffee, talks about a novel over hotpot; Blue at 11 PM searches Miyazaki and how to make an animated film. Main melody begins quietly.
```

## P-S017

```text
English class in Langzhong. Character Red stands and naturally chats with the teacher in English, jokes about forgetting homework, the class laughs warmly. Summer cicadas outside, warm red classroom light, slow push-in as the child's confidence fills the room.
```

## P-S018

```text
Mianyang math classroom in winter afternoon. Students leave after the bell, Character Gray remains alone, solving a difficult problem. Grass paper fills the desk, eraser becomes smaller, pencil lead shortens. Fixed wide shot slowly becomes tabletop close-up.
```

## P-S019

```text
University lab. Character Orange puts on headphones and enters flow. Sound reduces to keyboard, breathing and fan. Screen shows LeetCode Hard Submit, Loading, Accepted. Orange smiles very slightly and immediately opens the next problem. Focused close-ups of eyes, hands, screen.
```

## P-S020

```text
Beijing swimming pool in golden morning light. Character Gold swims lap after lap, smooth freestyle underwater, sunlight ripples over the body. Other swimmers rest on the side while Gold keeps going. After many laps, Gold stops, removes goggles, breathes and smiles quietly.
```

## P-S021

```text
Wudaokou wooden bookstore on a weekend afternoon. Character Gold sits by the window with a Dirty coffee and a Higashino Keigo novel. Tree shadows move outside. A WeChat message asks about hotpot tonight. Gold smiles, replies yes, continues reading. One long static shot, quiet happiness.
```

## P-S022

```text
Chengdu meeting room. Character Blue listens silently during a product requirement review, notices a logical flaw, raises a hand and says there is a problem. After the meeting, Blue searches for newly opened specialty coffee nearby. Eyes light up exactly like Character Red. Restrained office realism.
```

## P-S023

```text
Five-person flow montage. English book pages turn faster; math scratch papers pile up; code lines appear; bugs disappear; Blue writes a document titled Canlan while the content is hidden. Sunlight moves from morning to dusk outside each window. All five forget time. Rhythm gradually accelerates but stays elegant.
```

## P-S024

```text
Five people are called at almost the same time: English class representative, little sister, leader, engineer, Amory. Each person lifts the head in identical framing, but the actual names are covered by environmental sound. Same focal length, same eye line, no explanation.
```

## P-S025

```text
Five quiet nights: Red laughs on a phone call about math with friends; Gray hides under a quilt with a flashlight and exercise workbook; Orange is alone under the last lab light; Gold walks home with a partner while excitedly talking about Bai Ye Xing; Blue sits on a balcony with cold coffee, doing nothing, city lights appearing in the distance. End on Blue for twenty quiet seconds.
```

## P-S026

```text
Langzhong English classroom. Teacher asks what Character Red wants to do in the future. Red smiles and answers in English: I don't know, but I want to see a bigger world. Friends quietly clap and smile. Warm summer light, no heroic framing.
```

## P-S027

```text
Mianyang dormitory at 00:47. Under the quilt, Character Gray writes in a Mianyang High School exercise workbook by tiny flashlight. Scratch papers stack up. The pen stops. Gray has fallen asleep on the workbook, still holding the pen. Flashlight slowly dies to black.
```

## P-S028

```text
University programming contest aftermath. Orange team takes a photo, someone calls leader to stand in the middle. Flash. Cut to noisy dorm room with roommates gaming. Character Orange quietly places the medal at the deepest part of a bookshelf, opens LeetCode Hard and clicks Start. Screen lights the face.
```

## P-S029

```text
Beijing office with GitHub contribution grid full of green squares, merged PRs and approved reviews. Engineers are stuck on a crash. Character Gold walks over with coffee, watches silently, opens a file, scrolls, points to one line and says quietly: here. Compile passes, everyone exhales.
```

## P-S030

```text
Chengdu study at night. Character Blue sits before a Mac with many unread messages and a renovation contract nearby. Types: why does growing up feel more tiring, pauses, deletes everything, types: Miyazaki The Wind Rises. Screen light reflects in tired eyes, wind moves curtain, eyes become wet but no crying.
```

## P-S031

```text
Small bookstore near school in Langzhong. Red enters with friends, wanders to animation art books: Castle in the Sky, Totoro, Kiki, Spirited Away. Sound fades until only page turning remains. Red's eyes light up while touching a sky illustration. A friend calls: Canlan! Red turns and smiles. The name is heard clearly for the first time.
```

## P-S032

```text
Mianyang math class. The teacher draws a new auxiliary line on the blackboard. The class murmurs in realization. Character Gray quietly redraws the line on paper. At the moment the problem opens up, Gray's eyes light up. Close-up of the eyes and pencil line.
```

## P-S033

```text
Late-night university lab. Character Orange draws trees, arrows, arrays and recursion on a glass wall. Stops at one overlooked node, eyes light up, runs back to the laptop, deletes a large block of code, rewrites, submits, Accepted. No cheering, just a tiny nod.
```

## P-S034

```text
Beijing office. Everyone watches rolling logs, but Character Gold closes the log window and opens source code. Folds and unfolds functions, stops at one line, smiles slightly and says: found it. Run. PASS. Returns to desk before others fully react.
```

## P-S035

```text
Chengdu study. Character Blue generates an AI animated character again and again. Fourth generation: the character smiles for one frame. Blue's eyes light up, body leans forward, zooms in. This expression matches the young Red in the bookstore. Quiet screen glow, no fantasy effect.
```

## P-S036

```text
Five eye close-ups in hard cuts: Red, Gray, Orange, Gold, Blue. Each pair of eyes lights up in the same way. No dissolve, no face morphing. A single musical motif appears for the first time. The audience feels they somehow know each other.
```

## P-S037

```text
Montage of persistence: Red erases and restarts a math problem; Gray looks at the clock with fifteen minutes left and continues an exam; Orange gets Compile Error, gets water, returns and finds the issue; Gold handles a late-night online alert and says calmly: don't change it yet; Blue discovers renovation fraud, marks the contract with red pen, then makes a phone call. No argument shown.
```

## P-S038

```text
Time-passing montage: Red reads English until sunset; Gray writes one workbook then another until lights out; Orange codes until morning; Gold reads Bai Ye Xing through staff shift and coffee refill until dusk; Blue adjusts one animated smile until 03:18, saves, leans back and smiles with quiet tenderness. Fade to black.
```

## P-S039

```text
Five kinds of quiet smile, edited with identical rhythm: Red after English teacher praise; Gray after solving the final math step; Orange after Accepted; Gold after monitoring recovers from an online alert; Blue after AI animation finally gets the character right. Each smile is tiny, private, not triumphant. The music becomes lighter, like wind through five rooms.
```

## P-S040

```text
Five kinds of running: Red rides fast after friends through sunset Langzhong alleys; Gray runs with heavy books toward a steaming cafeteria; Orange runs through a university hallway hugging a laptop and gym bag; Gold runs through a Beijing crosswalk toward the swimming pool; Blue stands outside a gym after a long absence, ignores work messages, enters, ties shoes, starts slowly on a treadmill. Sounds merge into one rhythm.
```

## P-S041

```text
Five kinds of concentration shown through hands: Red marks English words at a desk; Gray draws auxiliary lines under a quilt; Orange draws algorithm trees on a whiteboard; Gold draws a system failure path in a meeting room; Blue draws storyboard boxes and a long table with five empty seats. Same thumb pressure on the pen, same wrist angle. No dialogue.
```

## P-S042

```text
Objects begin to speak: close-up of Red's English book with old-town card dated 11.18; Gray's workbook with birthday note from sister dated 11.18; Orange's lab sticky note saying Leader happy birthday 11.18; Gold's Bai Ye Xing bookmark with Langzhong landscape and 11.18; Blue's Mac date November 18, canlan folder, file 04_完整剧本.md. Blue drinks coffee and lightly frowns like the morning drink scene.
```

## P-S043

```text
Five eye-light moments in sequence: Red sees an animation art book with a girl looking at the sky; Gray sees a new math auxiliary line; Orange sees an overlooked algorithm boundary; Gold sees the true causal chain in code; Blue sees the eye expression in the AI-generated little girl. Continuous eye close-ups, no dissolves. Music stops, only Mac keyboard sound remains.
```

## P-S044

```text
Black screen. Four alarm clocks appear as sound only, one after another. The fifth morning has no alarm, only a coffee machine. Minimal, quiet, birthday morning.
```

## P-S045

```text
Langzhong bedroom morning. Red opens a small paper bag left by friends. Inside is a red gel pen and a note: happy birthday, English class representative. Red smiles and clips the pen to the English book. Warm curtain wind.
```

## P-S046

```text
Mianyang dormitory morning. Character Gray sits on the bed putting on the school uniform. From below the bunk, an older sister's hand passes a milk carton with a note: happy birthday, don't be too tired. Gray looks at the note and hides the milk deep in the schoolbag.
```

## P-S047

```text
University lab morning. Character Orange enters, everyone pretends not to look. Orange opens the laptop. At the instant the screen lights up, teammates pop up from under desks and push a small cake forward, clapping awkwardly. Orange freezes, then smiles.
```

## P-S048

```text
Beijing apartment morning. Character Gold returns from swimming, wet hair, towel dripping. Breakfast is on the table. Partner places a tiny cake in the corner and says: eat first. Gold looks at the cake, looks at partner, smiles, hangs the wet towel, sits down.
```

## P-S049

```text
Chengdu study morning. Character Blue sits at the Mac. Phone is quiet except work messages and a calendar reminder: November 18, birthday. Blue closes the reminder, makes coffee, opens a blank file named 04_完整剧本.md. The cursor blinks on an empty page. Static long shot, blue quietness.
```

## P-S050

```text
Five birthday flames: Red's friends stick a tiny candle into bread; Gray has a small cake with an unlit candle because fire is not allowed in the dorm; Orange's teammates use phone flashlights around a small cake; Gold has a stable real candle at the breakfast table; Blue lights an old scented candle alone in the study. All five close their eyes. Firelight becomes the same warm color.
```

## P-S051

```text
Chengdu study late night. Character Blue closes work software, renovation contract and messages. Only a blank document remains. Blue types the first Chinese character: 灿. The room sound changes. From far away come page turning, paper, keyboard, water and wind. Blue slowly raises the head. Slow push-in on hands and screen.
```

## P-S052

```text
Unknown memory room at night. Not a dream, not sci-fi. A real long wooden table under a warm lamp. Five subtle color zones: red, gray, orange, gold, blue. Red reads an English book, Gray writes exercises, Orange uses a laptop, Gold reads Bai Ye Xing with swim goggles nearby, Blue sits with a Mac. Nobody is surprised. Soft wind moves the curtain.
```

## P-S053

```text
Slow tabletop tracking shot across the long table: English book, milk note, small sun sticky note, swim goggles, coffee cup, red gel pen, exercise workbook, LeetCode screen, Bai Ye Xing novel, Mac. Ordinary objects arranged naturally. The answer emerges from life, not from exposition.
```

## P-S054

```text
Reveal through habits, not face morphing: Red touches the bridge of the nose; Gray adjusts glasses; Orange adjusts glasses; Gold touches the bridge of the nose; Blue touches the bridge of the nose. Then all lightly frown, then all smile the same tiny private smile. The audience understands they are the same person. No subtitles, no narration.
```

## P-S055

```text
Blue types the second Chinese character: 烂. The screen now reads 灿烂. Red, Gray, Orange, Gold and Blue look at the two characters. Five pairs of eyes light up in sequence. This time it feels like one shared light. Main melody returns gently.
```

## P-S056

```text
Five quiet completions: Red closes the English book after the last page; Gray finishes the final math problem; Orange submits the last code; Gold places the bookmark back into the novel; Blue presses save. The save indicator appears. Five closing sounds become one. Warm light dims slowly.
```

## P-S057

```text
Unknown room. Blue stands, walks to the door and looks back. The other four selves keep doing their own things: reading, writing, coding, reading. Blue smiles, understanding that the past selves never left. Blue turns off the light. Fixed distant shot, then black.
```

## P-S058

```text
Black screen. The five opening sounds return: Jialing River wind, Mianyang rice noodle steam, lab keyboard, Beijing swimming pool entry, Chengdu coffee machine. This time they sit calmly side by side. All stop. Title appears in Chinese: 灿烂. No subtitle, no explanation. Fade out.
```

---

# 角色参考图 Prompt

## 红 Reference

```text
Full body character reference sheet for Character Red, 13-15 year old Chinese student, short slim body, short slightly flipped hair, bright curious eyes, white school uniform, sneakers, bulky schoolbag, English book, warm red Langzhong sunset palette, neutral gender presentation, 2D hand-painted animation style, front view, side view, three-quarter view, simple clean background.
```

## 灰 Reference

```text
Full body character reference sheet for Character Gray, 16-18 year old Chinese boarding school student, rounder face, heavier body, slightly hunched shoulders, glasses, messy short hair, gray-white high school uniform, heavy exercise books, tired persistent eyes, winter gray palette, neutral gender presentation, 2D hand-painted animation style, front side and three-quarter views.
```

## 橙 Reference

```text
Full body character reference sheet for Character Orange, 18-22 year old Chinese university student, slim from fitness, focused sharp eyes, glasses, practical campus clothes, laptop, sports bottle, gym bag, calm leader energy, warm orange laboratory palette, neutral gender presentation, 2D hand-painted animation style, front side and three-quarter views.
```

## 金 Reference

```text
Full body character reference sheet for Character Gold, 22-26 year old Chinese software engineer and swimmer, strong healthy body, broad shoulders, open confident posture, short neat hair, warm eyes, simple office casual clothes, swim goggles, coffee cup, novel, golden Beijing winter sunlight palette, neutral gender presentation, 2D hand-painted animation style.
```

## 蓝 Reference

```text
Full body character reference sheet for Character Blue, 27-28 year old Chinese professional in Chengdu, gained weight compared with younger years, quieter posture, slightly tired eyes that still light up, glasses, simple home clothes and office cardigan variants, Mac laptop, coffee cup, renovation paper, calm blue night palette, neutral gender presentation, 2D hand-painted animation style.
```

---

# 场景参考图 Prompt

## Langzhong Reference

```text
Background concept art for Langzhong ancient town in Sichuan, gray tiled roofs, stone pavement, narrow old street, Jialing River wind, warm red sunset, small breakfast shop, bicycle passing, realistic Chinese architecture, soft hand-painted 2D animation background, no tourists crowding the frame.
```

## Mianyang Reference

```text
Background concept art for Mianyang boarding high school in winter, gray classroom, cafeteria with steaming rice noodles, dormitory bunk beds, foggy campus road, fluorescent light, quiet pressure, realistic Chinese school details, hand-painted 2D animation background.
```

## University Lab Reference

```text
Background concept art for Southwest Petroleum University lab, warm orange light, desks with laptops, whiteboard full of algorithms, glass wall for diagrams, sticky note with small sun doodle, quiet late-night campus outside, realistic and grounded, 2D hand-painted animation background.
```

## Beijing Reference

```text
Background concept art for Beijing Wudaokou winter life, clean apartment morning sunlight, office with monitors, swimming pool with golden light, wooden bookstore with coffee by window, realistic urban Chinese details, warm gold palette, 2D hand-painted animation background.
```

## Chengdu Reference

```text
Background concept art for Chengdu modern apartment study, Mac on desk, coffee machine, renovation contract papers, blue rainy night outside, warm desk lamp inside, quiet rebuilding mood, realistic home details, 2D hand-painted animation background.
```

## Memory Room Reference

```text
Background concept art for a real memory room, one long wooden table under warm lamp, curtain moving gently, five subtle light zones red gray orange gold blue, ordinary objects on table, no fantasy portal, no sci-fi, no glowing magic, quiet emotional realism, 2D hand-painted animation background.
```

---

# Prompt 质量检查清单

生成每个镜头后检查：

1. 角色年龄、体型、服装是否符合阶段。
2. 画面有没有误生成成科幻、穿越、魔法传送门。
3. 情绪是否克制，不能夸张哭笑。
4. 是否保留真实中国城市和学校细节。
5. ACT 4 的共振是否通过动作完成，而不是通过角色互相看见。
6. 片名、文件名、日期等文字只在指定镜头出现。
7. 结尾未知房间必须像真实记忆空间，不像梦幻舞台。
