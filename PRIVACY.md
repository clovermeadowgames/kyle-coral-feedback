# Kyle Coral playtest privacy (plain language)

**Short version:** we never collect anything that identifies you. The invite-only test build
shares an anonymous play log by default (the title screen says so, and you can turn it off in
Settings anytime). The public build sends nothing unless you turn it on.

## Bug reports

- **Bug reports are voluntary.** When you press **Esc → Report a Bug**, *you* choose to send it.
  It carries a game **seed**, the **level and version**, and whatever you type. Nothing about your
  identity, your files, or your system beyond the name of your operating system.
- **Reports are public.** They go to this feedback page, so anything you type here is public.
  Please leave out personal details.
- **All ages welcome.** A parent can file a report for a younger player. Please don't put a
  child's real name or contact details in a report.

## "Send Play Data"

There's a **Send Play Data** switch in **Settings** (in the pause menu and on the main menu). Its
starting position depends on which build you have:

- **Public build (the Steam demo, and the full game later):** **off**, and the game **asks first**.
  It only turns on if you say yes to a plain-language prompt that explains what's sent.
- **Invite-only test build** (including the Steam `playtest` branch the crew runs): **on**, because
  testers joined to help tune the game. The title screen says so the moment the game opens, and the
  switch is one step away.

Either way you can turn it **off at any time**. That stops all sending immediately, and the game
remembers your choice.

### What it sends when on

Only what happens **in play**:

- which levels you reach, how each dive ends, the level seed, and the game version
- the shape of each dive's economy: pearls found, gear you had left, and the gear and upgrades you
  dived with (so we can tell if players are over- or under-equipped for a depth)
- how often you refilled your air, and whether you were nearly out when you did
- whether **Assist Mode** was on for that dive (a plain on/off), so an eased dive is counted
  separately when we judge how hard a level really is
- whether the dive was in the optional **Rapture of the Deep** mode, for the same reason
- a rough sense of **how smoothly the game ran**: your frame rate, a broad graphics class (like
  "integrated" or "discrete"), and your window size as a rough bucket. Never your exact graphics
  card or any hardware ID.
- which **kind of computer** you play on (like Windows or Mac)
- **how many errors** the game hit in a session, as a single number and a broad "where" (menu,
  shop, cave, boss). Never the error text or any file name.

### What it never sends

Your name, your files, anything that identifies your computer or account, your location, or
anything you type.

### The one thing that persists

A single random tag, like a raffle ticket number, so we can tell whether the same copy of the game
was played again the next day, without ever knowing who or where you are. It's random characters
(nothing about your name, device, or account), it remembers only the *day* the game was first
opened (never a time), and it's only sent while Send Play Data is on. Play data is kept for up to
12 months, then deleted.

## Questions?

Open an issue here, or reply to your invite.
