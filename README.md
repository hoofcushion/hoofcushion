```lua
---@class Human
local self={
 ---@private
 info={
  name="Yuan Wenjie",
  ethnic="Han",
  gender="male",
  nationality="People's Republic of China",
  borntime=os.time({year=2006,month=10,day=8}),
 },
 nickname="Hoof Cushion",
 education={
  degrees={"Primary school","Junior middle school"},
 },
 language={
  spoken={"Mandarin","English"},
  written={"Simplified Chinese","English Letter"},
 },
 location={
  born="China, Hunan, Yueyang, Miluo",
  grow="China, Hunan, Chenzhou, Zixin",
  work="China, Hebei, Handan, Damin",
 },
 devices={
  phone={"Redmi Turbo 3"},
  laptop={"ThinkBook 16 G6 ABP"},
  mouse={"Logitech ERGO M575"},
  keyboard={"A4Tech FK11 USB"},
 },
 programming={
  language={"Lua"},
  style={
   indent={
    char={" ","\t"},
    size=1,
   },
  },
  paradigm={
   "Declarative",
   "Functional",
   "Procedural",
   "Object Oriented",
  },
  editor="Neovim",
 },
 interests={
  "Art",
  "Coding",
  "Internet",
  "Meme",
  "Music",
  "My Little Pony: Friendship Is Magic",
  "Neovim",
 },
}
return self
```
