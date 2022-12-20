# Better-Socialism
This is a mod of Victoria3

Match 1.1.2; support English, Chinese, Japanese and Korean.
For non-localized languages, the new text will be shown in English instead of code.

0.Summary
Modify the dividend mechanism of labor cooperatives and added new institution
New ownership production methods have been added to some buildings
Separate socialist market economy and command economy
The command economy has been redone, giving command economy a new experience
And some other fine-tuning

1.Ownership
(1)Worker Cooperative (Collective Ownership) [cannot be used in command economy]
The dividend of worker cooperatives has been modified. Now everyone enjoys the same dividend, not just machinists and laborers (all owners are workers, and all workers are owners)
*That is to say, the more profitable the factory is, the smaller the income percent gap between engineers and labors is, and the closer it is to common prosperity. (Labors and machinists of the vanilla worker cooperatives are the new privilege class, as engineers, shopkeepers and clerks all work for them.)
In addition, the cooperative will no longer add extra working population, and will remove the clergymen from the farms and pastures. 
*Even self supporting farms have no clergy in the cooperative mode, so why do more productive farms and pastures have clergymen?
The added recreation and sports centers in urban center(require the council republic to unlock)replace all clergymen with clerks, and have the same dividend mechanism as the worker cooperatives. 
Add worker cooperative to trade center, consist of shopkeepers and clerks in 1:3, which requires the council republic to unlock, and council republic no longer unlocks the government run ownership of the trade center

(2)Government Run (State Ownership) [only available in command economy]
Reduce Government Run bureaucratic posts fromv +150 per level to +100 per level (the same number of privately owned capitalists)
Accordingly, Government Run now consume administrative power:(per level)-1 for agriculture, fishery, forestry and urban centers, -1.5 for mining, -2 for industry and railway, and -0.5 for trade centers and academy of arts (subject to throughput efficiency)
Government Run will also remove the clergymen from the farms and pastures. 
Add government building to urban center, which requires command economy to unlock. Bureaucrats and clerks are in 1:3
Add government patronage to academy of arts, which requires command economy to unlock. Bureaucrats and scholars are in 15:85

(3)Others
The production method of the canal has been modified and the capitalists are replaced by bureaucrats. (After all, the canal has no dividend, and even the capitalists can only get wages. Are they capitalists? At most senior workers)

2.Law and Institution
(1)Council Republic
Add Development and Reform Commission(spend bureaucracy to regulate reproduction and promote economic development). 
Each level will increase the contribution rate of people in the worker cooperative to the investment pool by 5%, which will be unlocked by council republic and provide+5 maximum levels. 
*If you want to promote consumption, you can lower its level at any time (Since it is owned by the whole people, it is not surprising that people invest some money in extending reproduction)
The modifiers to council republic has been revised, it directly increases political power of trade unions by 10%, not that of technicians and farmers by 25%. Moreover,  it also reduces the political power brought by wealth by 20%.

(2)Command Economy
Command economy now levies 100% dividend tax (making your country really own the domestic industry run by the government, rather than being embezzled by the vanilla bureaucratic pop; of course, in the case of surplus bureaucracy and tax collection capacity)
The cost of the super control of command economy is to is to consume additional bureaucracy for your buildings
*In the later stage of the game, you will need a huge bureaucratic team to maintain the operation of command economy, which can simulate the difficulties encountered by the command economy in reality to a certain extent
In order to reduce the waste of administrative power, command econom will make Development and Reform Commission -4 the largest level (I don't know how to disable institutions in different law groups)

3.Some Supplements
Theoretically, it is compatible with most mods, as long as they don't change the worker cooperatives, government run, council republic, command economy and others I've changed. because I didn't directly modify the source file. Instead,I created new files to write what I need to change.

---------------

适配1.1.2；支持中文、英语、日语和韩语（不支持的语言显示英语而非代码）

0.概述 
修改了劳动合作社的分红机制，为其添加了新的机构 
为一些建筑添加了新的所有制生产方式 
分离了社会主义市场经济和计划经济 
重做了计划经济，让计划经济有船新的体验 
以及一些其他的微调

1.所有制
 (1)劳动合作社（集体所有制）[计划经济下不可启用] 
修改了劳动合作社的分红，现在所有人都享受相同的分红而不仅仅是技工和劳工（所有者都是劳动者,劳动者都是所有者）
*也就是说工厂越赚钱，工程师和劳工的收入相差比例越小，越接近共同富裕（原版合作社里的技工和劳工就是新的权贵阶级，工程师、店主和职员都给他们打工） 
此外，合作社不再增加额外的劳动人口，并且会移除农场和牧场的教士 
*连自给农场在合作社模式下都没有教士，那么生产力更发达的农场和牧场为什么会有教士？ 
城镇中心加入文体活动中心，需要委员会共和制解锁，把所有教士替换为职员，并且与劳动合作社有相同分红机制。 
贸易中心加入劳动合作社，店主和职员 1:3，同样是均等分红，需要委员会共和制解锁

(2)政府运营（国家所有制）[只在计划经济下可用] 
减少了了政府运营官僚岗位，从每级+150降低到每级+100（和私人所有的资本家数量相同）
相应地，政府运营现在需要消耗行政力：农业、渔业、林业、城镇中心每级-1，矿业每级-1.5，工业、铁路每级-2，贸易中心、艺术学院每级-0.5（会受吞吐效率的影响）
政府运营也会移除农场和牧场的教士
城镇中心加入政府大楼，需要计划经济解锁，官僚和职员 1:3
艺术学院加入政府资助，需要计划经济解锁，官僚和学者 15:85

(3)其他 
修改了运河的生产方式，把资本家替换成官僚（毕竟运河也没有分红，就算是资本家也只能领工资，这算资本家？顶多高级打工人）

2.法律和机构 
(1)委员会共和制 
新增发展和改革委员会（花费行政力，调控再生产，促进经济发展） 
每级增加劳动合作社5%投资池贡献率，由委员会共和制解锁，提供+5最大等级 
*如果你想要促进消费随时可以下调它的等级（既然是劳动者都是所有者，那么他们投点钱用于扩大再生产也没什么奇怪的吧） 
修改了委员会共和制的修正，现在直接增加工会10%政治力量而不是技工和农民的25%政治力量，还会减少20%财富带来的政治力量

(2)计划经济 
计划经济现在征收100%红利税（使你的国家真正拥有政府运营的本国产业，而不是被原版的官僚pop侵吞红利；当然，是在行政力和征税能力盈余的情况下） 
计划经济超强掌控力的代价是需要为你的产业建筑消耗额外的行政力 
*在游戏后期，你会需要一支庞大的官僚队伍去维持计划经济的运转，能在一定程度上模拟现实中计划经济遇到的困境 
为了减少行政力的浪费，计划经济会使发展和改革委员会-4最大等级（我不知道怎么在不同的法律组里禁用机构）

3.一些补充 
理论上和绝大部分mod兼容，只要它没改劳动合作社、政府运营、委员会共和制、计划经济以及其他我修改的内容，因为我没有直接修改源文件，而是另建文件去写我需要改的内容
如果发不了评论的话可以去V3贴吧找到"mod发布：更好的劳动合作社"来向我反馈:
https://tieba.baidu.com/p/8121586374
