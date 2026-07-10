---
system:
  name: DND5E
  edition: PHB24
character:
  id: character_dandan
  name: "蛋蛋"
  aliases: []
  player: null
  status: active
  tags:
    - player-character
    - cleric
    - support
    - phb24
identity:
  species: Human
  creature_type: Humanoid
  size: Medium
  class: Cleric
  subclass: null
  level: 2
  background: Hermit
  alignment: Neutral Good
  pronouns: null
  age: null
  height: null
  weight: null
  appearance: null
campaign:
  name: null
  character_status: active
  current_location: null
  in_game_day: null
  in_game_date: null
  party: []
  references:
    notes_file: null
    quests_file: null
    session_log_directory: null
    campaign_state_file: null
progression:
  leveling_method: experience
  current_xp: 736
  next_level: 3
  next_level_xp: 900
ability_scores:
  strength:
    score: 8
    modifier: -1
  dexterity:
    score: 14
    modifier: 2
  constitution:
    score: 16
    modifier: 3
  intelligence:
    score: 10
    modifier: 0
  wisdom:
    score: 16
    modifier: 3
  charisma:
    score: 10
    modifier: 0
combat:
  armor_class: 17
  initiative: 4
  speed_ft: 30
  proficiency_bonus: 2
  spell_save_dc: 13
  spell_attack_bonus: 5
  passive_perception: 15
  passive_insight: 15
  passive_investigation: 10
state:
  hp:
    current: 19
    max: 19
    temporary: 0
  hit_dice:
    current: 2
    max: 2
    die: d8
  death_saves:
    successes: 0
    failures: 0
  heroic_inspiration: true
  exhaustion: 0
  conditions: []
  concentration:
    active: null
  round_counter:
    current: 1
    effects: []
resources:
  channel_divinity:
    current: 2
    max: 2
    recovery:
      short_rest: 1
      long_rest: all
  spell_slots:
    level_1:
      current: 1
      max: 3
  healers_kit:
    current: 10
    max: 10
saving_throws:
  strength:
    bonus: -1
    proficient: false
  dexterity:
    bonus: 2
    proficient: false
  constitution:
    bonus: 3
    proficient: false
  intelligence:
    bonus: 0
    proficient: false
  wisdom:
    bonus: 5
    proficient: true
  charisma:
    bonus: 2
    proficient: true
skills:
  acrobatics:
    ability: dexterity
    bonus: 2
    proficient: false
  animal_handling:
    ability: wisdom
    bonus: 3
    proficient: false
  arcana:
    ability: intelligence
    bonus: 3
    proficient: false
    special_bonus: Thaumaturge
  athletics:
    ability: strength
    bonus: -1
    proficient: false
  deception:
    ability: charisma
    bonus: 0
    proficient: false
  history:
    ability: intelligence
    bonus: 0
    proficient: false
  insight:
    ability: wisdom
    bonus: 5
    proficient: true
    source: Cleric
  intimidation:
    ability: charisma
    bonus: 0
    proficient: false
  investigation:
    ability: intelligence
    bonus: 0
    proficient: false
  medicine:
    ability: wisdom
    bonus: 5
    proficient: true
    source: Hermit
  nature:
    ability: intelligence
    bonus: 0
    proficient: false
  perception:
    ability: wisdom
    bonus: 5
    proficient: true
    source: Human Skillful
  performance:
    ability: charisma
    bonus: 0
    proficient: false
  persuasion:
    ability: charisma
    bonus: 2
    proficient: true
    source: Cleric
  religion:
    ability: intelligence
    bonus: 5
    proficient: true
    source: Hermit
    special_bonus: Thaumaturge
  sleight_of_hand:
    ability: dexterity
    bonus: 2
    proficient: false
  stealth:
    ability: dexterity
    bonus: 2
    proficient: false
  survival:
    ability: wisdom
    bonus: 3
    proficient: false
proficiencies:
  armor:
    - Light Armor
    - Medium Armor
    - Shields
  weapons:
    - Simple Weapons
  tools:
    - Herbalism Kit
  languages:
    - Common
    - Dwarvish
    - Elvish
defenses:
  resistances: []
  immunities: []
  vulnerabilities: []
  condition_immunities: []
senses:
  darkvision_ft: null
  passive_perception: 15
  passive_insight: 15
  passive_investigation: 10
species_features:
  - name: Resourceful
    source: Human
    recovery: long_rest
  - name: Skillful
    source: Human
  - name: Versatile
    source: Human
feats:
  - name: Alert
    category: Origin Feat
    source: Human Versatile
  - name: Healer
    category: Origin Feat
    source: Hermit
class_features:
  - name: Spellcasting
    source: Cleric 1
  - name: Divine Order
    option: Thaumaturge
    source: Cleric 1
  - name: Channel Divinity
    source: Cleric 2
    resource: channel_divinity
  - name: Divine Spark
    source: Cleric 2
    resource: channel_divinity
  - name: Turn Undead
    source: Cleric 2
    resource: channel_divinity
spellcasting:
  ability: Wisdom
  ability_modifier: 3
  save_dc: 13
  attack_bonus: 5
  focus:
    item: Holy Symbol
    form: worn
    location: body
  prepared_spell_count: 5
  ritual_casting: true
  cantrips:
    - Guidance
    - Sacred Flame
    - Light
    - Resistance
  prepared_spells:
    level_1:
      - Bless
      - Healing Word
      - Cure Wounds
      - Sanctuary
      - Guiding Bolt
  available_spells:
    - name: Bless
      level: 1
      casting_time: Action
      range: 30 ft.
      tags:
        - Concentration
      effect: "最多 3 个目标，攻击掷骰和豁免检定额外加 1d4。"
    - name: Healing Word
      level: 1
      casting_time: Bonus Action
      range: 60 ft.
      tags:
        - "治疗"
      effect: "恢复 2d4 + 3 HP。Bonus Action，射程 60 ft.。"
    - name: Cure Wounds
      level: 1
      casting_time: Action
      range: Touch
      tags:
        - "治疗"
      effect: "恢复 2d8 + 3 HP。触碰施法。"
    - name: Sanctuary
      level: 1
      casting_time: Bonus Action
      range: 30 ft.
      tags:
        - "防护"
      effect: "目标被攻击时，攻击者须通过 WIS 豁免，否则须另选目标。"
    - name: Guiding Bolt
      level: 1
      casting_time: Action
      range: 120 ft.
      tags:
        - "爆发"
      effect: "远程法术攻击，命中造成 4d6 Radiant，下一次对目标的攻击有 Advantage。"
    - name: Detect Magic
      level: 1
      casting_time: Action
      range: Self
      tags:
        - Ritual
        - "探索"
      effect: "感知 30 ft. 内魔法灵光及其学派。"
    - name: Shield of Faith
      level: 1
      casting_time: Bonus Action
      range: 60 ft.
      tags:
        - Concentration
        - +2 AC
      effect: "目标 +2 AC。专注。"
    - name: Protection from Evil and Good
      level: 1
      casting_time: Action
      range: Touch
      tags:
        - Concentration
        - "防护"
      effect: "对特定生物类型获得攻击、防控和附身防护。"
    - name: Command
      level: 1
      casting_time: Action
      range: 60 ft.
      tags:
        - "控场"
      effect: "目标 WIS 豁免失败后执行一个单词命令。"
    - name: Detect Poison and Disease
      level: 1
      casting_time: Action
      range: Self
      tags:
        - Ritual
        - "调查"
      effect: "感知 30 ft. 内毒物、疾病及其种类。"
attacks:
  - name: Mace
    attack_bonus: 1
    damage: 1d6-1
    damage_type: Bludgeoning
  - name: Quarterstaff
    attack_bonus: 1
    damage: 1d6-1
    versatile_damage: 1d8-1
    damage_type: Bludgeoning
  - name: Sacred Flame
    attack_type: saving_throw
    save_ability: Dexterity
    save_dc: 13
    damage: 1d8
    damage_type: Radiant
  - name: Guiding Bolt
    attack_type: spell_attack
    attack_bonus: 5
    damage: 4d6
    damage_type: Radiant
equipment:
  equipped:
    armor: Chain Shirt
    shield: Shield
    main_hand: null
    off_hand: null
    spellcasting_focus: Holy Symbol
    focus_location: worn
  inventory:
    - name: Mace
      quantity: 1
    - name: Quarterstaff
      quantity: 1
    - name: Holy Symbol
      quantity: 1
    - name: Priest's Pack
      quantity: 1
    - name: Herbalism Kit
      quantity: 1
    - name: Bedroll
      quantity: 1
    - name: Book
      subtype: Philosophy
      quantity: 1
    - name: Lamp
      quantity: 1
    - name: Oil
      quantity: 3
    - name: Traveler's Clothes
      quantity: 1
    - name: Healer's Kit
      quantity: 1
      uses:
        current: 10
        max: 10
currency:
  cp: 0
  sp: 0
  ep: 0
  gp: 33
  pp: 0
  needs_update: true
notes:
  freeform: |
    当前地区的神：
    主要 厄拉西斯, 授律者
    次要 肚皮神
    
    吟游诗人信息
    每一段时间会有黑潮
    当地神职人员会采购大量物资，但是不知道去哪里，黑潮是因为恶魔入侵人间，因为恶魔儿子被斩杀
    
    吟游诗人有问题，衣服的质感很好，不像是个传统的吟游诗人。怀疑琴弦有魔法加持。袖口有 belly god。感觉言行狂放，但是并不偏激，大概率是个好人。但是值得调查。
    
    法师导师东北部
    
    任务
    吟游诗人任务
    [ ] 1. 夜晚悄悄的去神像上画污秽的东西
    [ ] 1.1 宣扬肚皮神教很好
    [ ] 2. 黑暗生物首领的首级
    
    牧师任务
    [ ] 1. 采购100斤大米
    [ ] 2. 采购5黑水晶
    [x] 3. 清除北部丧尸 （北 3-4km 安全，再北面有浅河，过河危险）
    
    混乱 + 4
  personal_objectives: []
  reminders: []
---

# 角色概念

蛋蛋并非传统意义上的宗教信徒，而是将神术视为一种可以研究和使用的外层位面能量现象。

他认为能救人优先于解释意义，权威需要接受检验，神术是一种工具而不是服从体系。

# 背景故事

蛋蛋出生于偏远山路驿镇，早年接触瘟疫、伤患和旅行者救治。

一次热病事件中，他目睹神殿体系因仪式和规则导致救援迟缓，从而形成了对宗教权威的不信任。

之后，他跟随隐居草药师学习医学、记录和观察神术现象。他最终发现自己能够引导类似神术的力量，但拒绝将其解释为神明恩赐，而认为这是某种可以研究的外层位面现象。

现在他作为牧师旅行，使用神术救助他人，但拒绝成为任何神殿体系的传声筒。

# 性格

## 性格特征

直接、务实，优先解决现实问题，不喜欢仪式感和空泛安慰。

## 理念

任何权威都必须接受检验；能减少伤亡的选择优先于漂亮口号。

## 羁绊

曾经的驿镇、隐居导师，以及所有被神殿规矩耽误过的人。

## 缺点

对宗教组织和神职头衔过度警惕，有时会把普通信徒也误判为权威体系的帮凶。

# 剧情钩子

- 蛋蛋的隐居导师失踪，留下的笔记指向某个神殿封存的医疗实验。
- 当年热病时期的巡回祭司如今成为高阶神职者，并可能正在掩盖旧事。
- 蛋蛋的神术来源可能并非传统神祇，而是某个与生命延续相关的外层存在。
- 某个村庄将蛋蛋误认为圣人并试图建立崇拜。

# Notes

当前地区的神：
主要 厄拉西斯, 授律者
次要 肚皮神

吟游诗人信息
每一段时间会有黑潮
当地神职人员会采购大量物资，但是不知道去哪里，黑潮是因为恶魔入侵人间，因为恶魔儿子被斩杀

吟游诗人有问题，衣服的质感很好，不像是个传统的吟游诗人。怀疑琴弦有魔法加持。袖口有 belly god。感觉言行狂放，但是并不偏激，大概率是个好人。但是值得调查。

法师导师东北部

任务
吟游诗人任务
[ ] 1. 夜晚悄悄的去神像上画污秽的东西
[ ] 1.1 宣扬肚皮神教很好
[ ] 2. 黑暗生物首领的首级

牧师任务
[ ] 1. 采购100斤大米
[ ] 2. 采购5黑水晶
[ ] 3. 清除北部丧尸 （北 3-4km 安全，再北面有浅河，过河危险）

混乱 + 4
