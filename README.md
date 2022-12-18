# Better-Socialism
This is a mod of Victoria3

1.Ownership
The dividend of worker cooperatives has been modified. Now everyone enjoys the same dividend, not just machinists and laborers (real ownership by the whole people)
That is to say, the more profitable the factory is, the smaller the income percent gap between engineers and labors is, and the closer it is to common prosperity. (Labors and machinists of the vanilla worker cooperatives is the new privilege class, as engineers, shopkeepers and clerks all work for them.)
In addition, the cooperative will no longer add extra working population, and will remove the clergymen from the farms and pastures. (as they get money for doing nothing, even self supporting farms have no clergy in the cooperative mode, so why do more advanced and productive farms and pastures have clergymen? )
The newly added recreation and sports center in urban center needs to be unlocked by the non state religion and the council republic, replace all clergymen with clerks, and have the same dividend mechanism as the worker cooperatives. Now you have an opportunity to completely eliminate religious forces in your country
Add worker cooperative to trade center, consist of shopkeepers and clerks in 1:3, which requires the council republic to unlock, and council republic no longer unlocks the government run ownership of the trade center (after all, except for this, all government runs are unlocked by the command economy)
The production method of the canal has been modified and the capitalists are replaced by bureaucrats. (After all, the canal has no dividend, and even the capitalists can only get wages. Are they capitalists? At most senior workers)

2.Law and Institution
The new Development and Reform Commission(spend bureaucracy to regulate reproduction and promote economic development) is added. Each level will increase the contribution rate of people in the worker cooperative to the investment pool by 5%, which will be unlocked by council republic and provide+5 maximum levels. If you want to promote consumption, you can lower its level at any time (Since it is owned by the whole people, it is not surprising that people invest some money in extending reproduction)
The modifiers to council republic has been revised, and now the political power of trade unions is directly increased, not that of technicians and farmers (After all, directly adding political power of a certain type of occupation should be the effect of the power distribution law)
The command economy now make bureaucrats hand in all their dividends (which can be used to build any industry), and is no longer mandate subsidies, so that your country really has its own industry run by the government, instead of being occupied by pop called bureaucrats who are actually capitalists in the vanilla game, The cost of the super control of the command economy is to increase the bureaucracy population cost multiplier by 25% (of course, the government operation is more inefficient than other ownership systems in terms of wage spending, but it has strong potential, which can achieve the effect of concentrating on major issues)

Theoretically, it is compatible with most mods, as long as they don't change the worker cooperatives, council republic and command economy because I didn't directly modify the source file. Instead,I created new files to write what I need to change

0.概述
修改了劳动合作社的分红机制，为其添加了新的机构
为一些建筑添加了新的所有制生产方式
分离了社会主义市场经济和计划经济
重做了计划经济，让计划经济有船新的体验
以及一些其他的微调

//且委员会共和制不再解锁贸易中心的政府运营所有制（毕竟除了这个，所有政府运营都是由计划经济解锁的）
1.所有制
(1)劳动合作社(集体所有制)[计划经济下不可启用]
修改了劳动合作社的分红，现在所有人都享受相同的分红而不仅仅是技工和劳工（所有者都是劳动者,劳动者都是所有者）
*也就是说工厂越赚钱，工程师和劳工的收入相差比例越小，越接近共同富裕（原版合作社里的技工和劳工就是新的权贵阶级，工程师、店主和职员都给他们打工）
此外，合作社不再增加额外的劳动人口，并且会移除农场和牧场的教士
*连自给农场在合作社模式下都没有教士，那么生产力更高的农场和牧场为什么会有教士？
城镇中心加入文体活动中心，需要委员会共和制解锁，把所有教士替换为职员，并且与劳动合作社有相同分红机制。（现在你有机会完全消灭国内的宗教势力）
贸易中心加入劳动合作社，店主和职员 1:3，同样是均等分红，需要委员会共和制解锁

(2)政府运营(国家所有制)[只在计划经济下可用]
减少了了政府运营官僚岗位，从每级+150降低到每级+100(和私人所有的资本家数量相同)
相应地，政府运营现在需要消耗行政力：农业、渔业、林业、城镇中心每级-1，矿业每级-1.5，工业、铁路每级-2，贸易中心、艺术学院每级-0.5(会受吞吐效率的影响)
城镇中心加入政府大楼，需要计划经济解锁，官僚和职员 1:3；艺术学院加入政府资助，官僚和学者 15:85

(3)其他
修改了运河的生产方式，把资本家替换成官僚（毕竟运河也没有分红，就算是资本家也只能领工资，这算资本家？顶多高级打工人）

2.法律和机构
(1)委员会共和制
新增发展和改革委员会（花费行政力，调控再生产，促进经济发展）
每级增加劳动合作社5%投资池贡献率，由委员会共和制解锁，提供+5最大等级
*如果你想要促进消费随时可以下调它的等级（既然是劳动者都是所有者，那么他们投点钱用于扩大再生产也没什么奇怪的吧）
修改了委员会共和制的修正，现在直接增加工会10%政治力量而不是技工和农民的25%政治力量，还会减少20%财富带来的政治力量

(2)计划经济
计划经济现在增加100%红利税（使你的国家真正拥有政府运营的本国产业，而不是被原版的官僚pop侵吞红利）
计划经济超强掌控力的代价是需要为你的产业建筑消耗额外的行政力
*在游戏后期，你会需要一支庞大的官僚队伍去维持计划经济的运转，能在一定程度上模拟现实中计划经济遇到的困境
为了减少行政力的浪费，计划经济会使发展和改革委员会-4最大等级（我不知道怎么在不同的法律组里禁用机构）

3.一些补充
理论上和绝大部分mod兼容，只要它没改劳动合作社、政府运营、委员会共和制、计划经济以及其他我修改的内容，因为我没有直接修改源文件，而是另建文件去写我需要改的内容
