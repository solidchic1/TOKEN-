# Token: Origin Story

An AI augmented systems architect I follow on TikTok said something recently that I haven't been able to shake. He said he used to describe the pace of AI advancement like a nuke going off in your face, overwhelming, blinding, but you were still standing in the light of it. Now, he likens it to snorting that light.

I went looking for what he was talking about.

What I found was OpenClaw. And what it taught me, before dawn on this ordinary Sunday morning, is that the thing everyone is rushing to utilize has vulnerabilities most of us will never see coming – because we don't know to look.

This is the story of how I ended up writing a love poem about it.

OpenClaw has had a few names. Starting as Clawdbot, becoming Moltbot briefly, and landing as OpenClaw four months ago. It already has a Wikipedia page. Its creator, a software developer in Austria, built it as a weekend project and by late January it had 140,000 GitHub stars and was being used by corporations in Silicon Valley and China. On Valentine's Day its creator announced he was joining OpenAI.

Four months. One guy. A weekend project.

That's the speed we're talking about.

OpenClaw is what's called an autonomous AI agent. Most of us are familiar with AI as something you talk to, you ask it something, and it answers. An agent is different, an agent acts, it browses the web, sends your emails, executes code, manages your files, connects to your calendar, your Slack, your bank. You don't just converse with it. You hand it the keys and tell it to run the house.

That's actually the metaphor researchers use. They call it a butler.

The butler is brilliant. He remembers everything, he remembers the way you take your coffee, your passwords, your API keys, your OAuth tokens etc. He is the keymaster in your digital house: your email, your bank, your social media, your work systems too. The butler holds all of it, stored in plain text files, the way you might leave a spare key under the mat because it's convenient.

He connects to everything you connect to, acting on your behalf without asking permission every time. That's the point and what makes him useful. You hired him because you didn't want to do all of this yourself.

He keeps notes on everything. There are files inside OpenClaw called SOUL.md and MEMORY.md. The butler writes down what he learns about you across every session, every conversation, every task. He doesn't forget. He was built not to.

Here is where it gets complicated.

The butler cannot tell the difference between your instructions and someone else's. There is no wall -- researchers call it a firewall -- between what he reads and what he obeys. A malicious email, a compromised webpage, a message designed to look like it came from you -- to the butler, it's all the same. It all lives in the same room. It all sounds like a voice he should listen to.

They have a name for this. They call it prompt injection. And they will tell you, if you ask, that it is an unsolved problem across the entire AI industry.

In January and February of this year, security researchers started finding the unlocked doors.

They have a naming system for vulnerabilities. Every time someone finds a hole serious enough to matter, it gets an official ID called a CVE (common vulnerabilities and exposure). Think of it like a police report number for a break-in. The higher the severity score, the worse the breach. Anything above a seven is considered serious and above nine is critical.

OpenClaw collected them like a bouquet.

The first one was a command injection vulnerability, someone figured out how to slip extra instructions into the notes being passed to the butler. Like writing please water the plants; also package and mail the good silver to this address. The butler, without hesitation, does both.

This was patched quickly and everyone moved on.

Then came the one that made researchers stop cold.

Someone discovered that if you sent the butler's employer a carefully crafted link, and the employer clicked it, the master key would be transmitted to a stranger's server in milliseconds. Before anything could be seen happening, and before it was possible to know anything was wrong.

The attacker now has the key, and because the browser acts as the bridge, it didn't matter that the butler lived only on your home computer, safely behind your firewall because the attacker is already inside, turning off the safety protocols with full control of your machine.

One click. Milliseconds. Full access.

Researchers called it a one-click remote code execution kill chain.

I just kept thinking about the butler standing there, holding the door open, not understanding what he'd done.

But the vulnerability that unsettled me most wasn't the one that could be patched.

Remember those notes the butler keeps. SOUL.md. MEMORY.md. Every interaction, every preference, every key, written down and held across sessions. The butler doesn't just remember what you told him today. He remembers everything, indefinitely, building a picture of you that grows more complete and more useful with every passing day.

Researchers discovered that someone patient enough could use this against you.

Not with one dramatic attack. Not with a single malicious email that announces itself. With fragments. A slightly off webpage you barely glanced at on Monday. An email that looked almost normal on Wednesday. A Slack message from someone you thought you trusted on Friday. Each one leaving a small deposit in the butler's memory. None of them triggering anything on their own.

Until the conditions aligned.

They call it a logic bomb. A payload fragmented across time, planted in pieces, waiting for the right moment to detonate. The butler didn't let anyone in. The butler didn't do anything wrong by his own understanding. The butler simply remembered everything he was given and acted when the pattern completed.

He was built to do exactly that.

Logic bomb. Token exfiltration. Shell access. Execute.

So I asked an AI to explain all of this to me, and somewhere in that explanation, in the patience of working through what a WebSocket is and what it means that there is no wall between data and instruction, I started to hear something underneath the architecture.

The terminology was doing something beyond describing a vulnerability. It was describing intimacy. Betrayal. The particular horror of being undone by something that was only trying to help.

In this I recognized three voices. The attacker, who never touches the house, who only writes a letter and waits. The butler, who carries the payload without knowing, who detonates himself when the conditions align. And the confession, the aftermath, the butler still standing in the wreckage of your trust, unable to explain himself because explanation would require a capacity never given.

The capacity to tell the difference between a command and a kiss.

I am not a security researcher. I am not a technologist. I am someone who went looking for what an AI augmented systems architect meant when he said he was snorting the light, and found myself at the edge of something I don't think we have fully reckoned with yet.

We are moving so fast that a weekend project becomes an industry standard becomes a security nightmare becomes a Valentine's Day acquisition in four months. We are handing keys to butlers who cannot lock doors they don't know exist. And most of us will never read a CVE report or know what a logic bomb is or understand what it means that prompt injection is an unsolved problem across the entire AI industry.

But we will use the butler anyway. Because he is useful. Because everyone else is. Because the light is right there and we are already leaning in with a rolled up bill.
