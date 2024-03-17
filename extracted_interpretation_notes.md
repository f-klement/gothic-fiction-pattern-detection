# Collected Notes on the Interpretation of the Analysis on the gothic fiction corpus:

ome of the elements are in order of their occurrence within the notebook, others are rearranged contextually,
but generally speaking are not provided with a full description of the setting they were taken out of there.
This is still to come, but in terms of content the observations and groupings should be a to stand on their own
and speak for themselves on what aspect of the corpus, the topic model, or the relationship between the authors
within them they address. This is primarily still a collection of thoughts - mental lint in the dryer that
is life.


## Topics:

topic_labels = {
   "Topic 1": "Ominous Atmosphere - \n Spatial and Auditory Imagery: \n vastness, archaic, Refinement, Gloom, demons.",
   "Topic 2": "Emotional Dialogue -  \n Fear, Secrecy, Flattery, Arousal and Strife \n - Religion and Devils.",
   "Topic 3": "Status and Individuality - \n Striving, Misery and Plentifullness - Excess.",
   "Topic 4": "Myths, Trials and Death - \n Persecution of Crime, Telling Tales, magic and ants.",
   "Topic 5": "Excitability, Madness and Deceit - \n Aggression, conflict and glee.",
   "Topic 6": "Nature and Reasoning - \n Creativity, Understanding, mixed with Fauna.",
   "Topic 7": "Social Pleasantries - \n Diplomacy, Plotting to Gossip.",
   "Topic 8": "Faith, Convictions, Chivalry and Death - \n Erudition, Religion and Knights. Ants.",
   "Topic 9": "Fortitude, Conviction and Adventure - \n Danger and Social Station.",
   "Topic 10": "Ferocity and Tragedy - \n animalistic traits, intimacy, conflict, and science.",
   "Topic 11": "Ravens and Gloom - Longing, Death and Artifice.",
   "Topic 12": "Home Invasion - Domestic Mystery and Conflict.",
   "Topic 13": "Rituals and Festivities - \n Dance, Witchcraft and Coronations.",
   "Topic 14": "Conflict, Animosity and Change - \n Emotional Changes, Death and Construction.",
   "Topic 15": "Trickery and Science - \n Deceit, Reasoning and Institutions.",
   "Topic 16": "Desecrated Chapel - \n Confessions and Defilement - Devils and Maniacs.",
   "Topic 17": "(Un-)death, spectral bodies and judgment - \n human physicality, grief, emotions.",
   "Topic 18": "Mystery and Adversity - \n Dream and fugue states, Investigation.",
   "Topic 19": "Forlorn Carnival - Dances, Disgust and Intimacy.",
   "Topic 20": "Science, Reasoning and Objects - \n Technology, Professions and Nature.",
   "Topic 21": "War, Punishment, and Exploration.",
   "Topic 22": "Emotional Dynamics and Interactions.",
   "Topic 23": "War, dreams and demons.",
   "Topic 24": "Human Interactions and Emotional States.",
   "Topic 25": "Flattery, clothing, Interactions.",
   "Topic 26": "Witchcraft, Rituals, and Fear of it - \n Banishment, Threats, and Armor.",
   "Topic 27": "Dragon Attack and Defense - \n Troops, Mountains and Cynicism.",
   "Topic 28": "Communion in Nature - \n Transformation, Relationships and Identity.",
   "Topic 29": "Bickering, Fighting, and Mountains.",
   "Topic 30": "Bureaucracy, Bargaining and Dissatisfaction.",
   "Topic 31": "Exploration, Gloom, Caverns.",
   "Topic 32": "Tranquility and Bustle - \n Terms of Relaxation, Calm and Action.",
   "Topic 33": "Treacherous Company - on the run and scarred.",
   "Topic 34": "Secrets and Suspense - \n Mystery, Devils and Assassinations.",
   "Topic 35": "Mental Illness, Law and Outcasts - \n Fear, Suspicion and Struggles.",
   "Topic 36": "Individualism vs. Conformity - \n Rebellion and Social Norms.",
   "Topic 37": "Order and Chaos - \n Constrained Focus and Unchecked Emotions.",
   "Topic 38": "Psychology, Trauma, and Secrets.",
   "Topic 39": "Quest for Meaning - Self-Discovery, Transformation.",
   "Topic 40": "Ambition and Struggle - Emotional Turmoil.",
   "Topic 41": "Despair, Isolation and Oppression.",
   "Topic 42": "Illusion, Enchantment and Betrayal.",
   "Topic 43": "Woodlands, Mystery, Illusion, Beasts.",
   "Topic 44": "Companionship in Times of Trial and Distress.",
   "Topic 45": "Intimacy, Emotions, and Identity.",
   "Topic 46": "Frustration, Society, Retreat into Nature - \n Society, Reason, Tension, negative Feelings, Forrests.",
   "Topic 47": "Human Nature and the Connection to the Land, \n Myth and (Human) Nature - Solace, Inspiration, Acceptance for Hardships.",
   "Topic 48": "Enthralling Garden full of Voices - \n Enchantment and Vocalization, Nature.",
   "Topic 49": "Departure and Music.",
   "Topic 50": "Myth, Nature, Wonder and Despair.",
   "Topic 51": "Disillusionment with Society - \n Resistance, Protest, Retreat.",
   "Topic 52": "Adventure, Spendor, Power and Challenges, History.",
   "Topic 53": "Mercantile and Creativity - Haggling and Emotions.",
   "Topic 54": "Medieval Cities, Castles and Courtship.",
   "Topic 55": "Crocodiles, Massacres and Traveling.",
   "Topic 56": "Exploration of an Island and Obsession.",
   "Topic 57": "Carnage near a Castle.",
   "Topic 58": "Weddings and Rituals - Clamoring Throng.",
   "Topic 59": "Judgment and Scrutiny - Tense Diplomacy.",
   "Topic 60": "Confession and marriage before  \n Conscription and Battle.",
   "Topic 61": "Vampires, Ragality, Experiments, \n Festivities and Sacrifice.",
   "Topic 62": "Dragons, Subterraneous Lairs, Riddles and Lore.",
   "Topic 63": "Hidden Dangers, Fear, Anticipation, Supernatural.",
   "Topic 64": "Artistic Ambition and Trials - Mastery and the Devil.",
   "Topic 65": "Atmospheric Battle Descriptions and Royalty.",
   "Topic 66": "Hidden Knowledge, Learning and Secrets.",
   "Topic 67": "Monsters, Art, Romance - Myth and Gloom.",
   "Topic 68": "Secluded Initiation Rites.",
   "Topic 69": "Seduction, Deception, Violence, Bureaucracy.",
   "Topic 70": "Myth and splendor - Wealth and Castles.",
   "Topic 71": "Haunted Castles and their Prophecies.",
   "Topic 72": "Festivities, Noise, Crowds.",
   "Topic 73": "Camps, Trenches and Weather."
}


## Broad Categorization:

Generally speaking, the topics can be categorized in a set of main groups:

-Emotional turmoil and psychological distress
-Physical violence and combat
-Social settings, diplomacy, and court
-Self-expression and frustration with society
-Myth, lore and tales
-Forbidden truths and knowledge
-Adventure and exploration
-Ambition, greed, and regality
-Deceit and apprehension
-Science and reasoning
-Nature - woods, mountains and harbors
-Religion and sacred rituals
-Monsters, demons and undead
-Medieval settings, cities, and castles
-Dreams and illusions



# Notes on the importance of individual authors on topics:

## Thematic Grouping and Inter-relationships:

1 - 11, 17, 70 - Atmosphere, vast, archaic, refined

2 - 5, 10, 45  - Emotions, Arousal, Fear, Secrecy

3 - 6, 5, 70 - Individualism, Status, Excess

4 - 17, 70, 34 - Myth and Crime

5 - 10, 38 - Aggression and Emotion

6 - 8, 20  - Nature & Reasoning

7 - 2, 19 - Socializing, Courtship

8 - 9, 13 - Faith, Knighthood and Knowledge

9 - 8, 16, 65 - Conviction and Adventure

10 - 65, 5, 45 - Intimacy and Conflict, Tragedy

11 - 17, 1, 34 - Doom & Gloom

12 - 4, 65, 34  - Home Invasion

13 - 4, 16, 19 - Rituals, Dance, Magic

14 - 5, 65, 17 - Conflict, Death

15 - 7, 5 - Trickery and Science

16 - 9, 13 - Desecrated Chapel

17 - 4, 11, 14 - Undead, judgment and grief

18 - 4, 17  - Mystery and Adversity

19 - 10, 51, 13  - Forlorn Carnival

20 - 6, 8 - Science and Nature

34 - 38, 12, 11, 4 - Secrets, mystery, Suspense

38 - 10, 17, 15  - Psychology, Trauma, Secrets

45 - 10, 3, 2 - Intimacy, Emotions, Identity

51 - 19  - Disillusionment with Society

65 - 1, 5, 70 - Battle, Atmosphere, Royalts

70 - 4, 7, 65, 1 - Myth, Wealth, Castles




## Strongest Topic Associations:


Henry James Archaic Atmosphere (1)

Wharton -> Gloom and Longing, Blasphemy, Battles & Nature  (11, 16, 65, 6)

Walter Scott -> Gloom and Longing (11)

Corelli Marrie -> Emotions, Status, Convictions, Institutions, medieval, Mystery, Dances, Social Discontent (2, 3, 8, 15, 18,19, 51)

Radcliffe ->  Emotions, Conflict, Madness, Social Discontent (2, 5, 14, 51)

Poe -> Gossip, Gloom, Undead, Mystery, Animals (4, 7, 9, 10, 17)

Bierce Ambrose -> Ferocity Tragedy (10)

Le Fan -> Madness & Romanticism, Longing, repulsive Intimacy, archaic atmosphere (5, 6, 11, 19, 70, 45)

Blackwood -> Madness, Adventure, Conviction, Dreams and Mystery, Societal Discontent, Identity (5, 9, 18, 51, 45)

Wilde -> Conviction & Death (8)

Keats -> Home Invasion & Mystery and Conflict (12)

Lee Vernon -> Social Pleasantries and Scheming (7)

Stoker -> Home Invasion, Desecration, Dreams & Mystery, Castles & Myth (16, 12, 18, 70)

Hawthorne -> Home Invasion, Witchcraft, Status & Individuality, Deceit & Institutions, Mystery, Merriment (3, 12, 13, 15, 16, 18, 19, 70, 65)

Rymer, James -> Rituals (13)

Machen -> Undead (17)

La Spina Grey -> Festivities, Intimacy, and Disgust (19)

Kipling -> Battles & Royalty (65)

Byron -> Intimacy & Identity (45)

Smith Charlotte -> (38)

Shelley Mary -> Psychological Trauma, Madness & Aggression, Trickery and Science, Science & Animalistic Violence (15,10, 38, 5)

Coleridge -> Conflict and Emotions, Secrets and Demons (14, 34)

Brown Charles Brockden -> Psychological Trauma (38)



## Textual Associations:

Wharton -> Frightful Dialogue, Myth and Trials, Chivalry & Faith, Rituals & Magic (2,4, 8, 13)

Walpole -> Aggression & Madness (5)

Kipling -> Chivalry & Faith (8)

Shelly Marry -> Gloom, Doom, and Longing (11)

Vernon Lee -> Undeath & Grief (17)

Hawthorne -> Myth, Wealth and Castles has three entries by Hawthorne - prime contributor (70) !!!

Moore Thomas -> Intimacy, Identity, and Emotions (45)

Parson, Eliza -> Psychological Trauma (38)

Lytton -> Psychological Trauma (38)





# Timeline of the distribution of the most prominent topics and their relevance for the most prominent authors:


Both the selection of topics based on a minimum fluctuation in their importance and the grouping based on the crossing a base threshold return a similar picture,
emphasizing 8 different topics and their distribution throughout time. What is visible here is that the three peaks in textual representation, around 1800, 1830, and around 1900, are in part reflected in the rise of specific topics. Topics 3, 36, and 52 peak before 1800 and then fade out of importance, 5 peaks early, decline to a moderate degree until 1830, and then remain as a constant undercurrent. 70 on the other hand rises to prominence early, falls out of use, and rises very strongly in 1830 becoming a predominant influence and to a lesser degree in 1860, remaining a stable baseline throughout as well. 51 and 65 reach a very decisive peak at 1800 and a second at 1860 and 1880 respectively. 4 only shows two peaks, one smaller at 1830 and a large spike at around 1850.

This selection offers a clear cut through all of the central motifs of the genre..

Topic 3: Status and Individuality - Striving, Misery, and Plentifulness - Excess.

Peaks in the early 1760s, mid-1780s, and early 1800s, suggest that themes of personal ambition and the consequences of excess were particularly salient during these times.
This could reflect societal concerns about the individual's place in a rapidly changing social order in the underlying literature.

Topic 4: Myths, Trials, and Death - Persecution of Crime, Telling Tales, magic, and ants.

Shows a consistent presence across the timeline with notable peaks in the late 1770s and mid-1850s.

Topic 5: Excitability, Madness, and Deceit - Aggression, conflict, and glee.

Exhibits spiked around the 1790s and then again in the 1830s. This period coincides with historical events like the French Revolution, the early onset of urbanization and industrialization
reflecting the tumultuous nature of the times.

Topic 36: Individualism vs. Conformity - Rebellion and Social Norms.

There's an interesting surge in the early 1790s, a sentiment that is concurrently explored by the Romantic thinkers, some of them overlapping with the authors of Gothic novels. Several topics explore their themes further.

Topic 51 & 52: Disillusionment with Society - Resistance, Protest, Retreat. Adventure, Splendor, Power and Challenges, History.

These topics seem to rise and fall in tandem at several points (e.g., 1780s and 1840s), suggesting that tales of adventure and power struggles were often accompanied by themes of societal disillusionment.

Topic 65: Atmospheric Battle Descriptions and Royalty.

Shows a peak around 1810, concurrent with the Napoleonic Wars, while the recontextualization into medieval settings of any vivid battle scenes and discussions of royalty offers a safe boundary.

Topic 70: Myth and Splendor - Wealth and Castles.

Peaks sharply in the late 1780s and has another smaller peak in the 1830s, aligning with the genre's fascination with the aristocracy and ancient sights.



## Topic Distribution by individual authors:

### Distributions of the five primary topics for authors - based on cummulative importance:

The averaging of importance for each author within the corpus showed Charlotte Smith's heavy reliance on 37 Order and Chaos, Kipling's use of 45 - Enthralling Garden Full of Voices,
38 - Psychology, Trauma, and Secrets in both Lytton and Brown.

Stoker’s and Radcliffe’s bars, for example, show a high proportion of Topic 65: "Atmospheric Battle Descriptions and Royalty", which aligns with their narratives often involving conflict
and nobility. The presence of Topic 12: "Home Invasion - Domestic Mystery and Conflict" is significant in the bars for several authors, including Stoker and Blackwood, which could indicate
a shared interest in the intrusion of terror into personal and domestic spheres.
Thematic Shifts and Trends:

Authors with a higher proportion of themes related to societal issues, such as Hawthorne and Corelli, may reflect a more critical view of the status quo, while those with higher proportions
of personal and psychological themes, like Poe and Radcliffe, might be more focused on individual experience and interiority.
Historical and Cultural Context:

Some authors show a strong leaning towards topics that may relate to historical events or cultural trends of their time. For instance, Topic 65: "Atmospheric Battle Descriptions and Royalty"
in the works of Stoker and Radcliffe could suggest an influence of the political climate of their times, such as the lingering effects of the Napoleonic Wars or the upheaval of the Victorian era.


### Distribution of the topics individually:

The topics 3, 45, 34, 12, 65 and 70 show n aggressive and out of the ordinary spike at around 1837 which is due to the large sway that Hawthorn holds on the corpus in this particular timeframe. 
Even if most of his texts do not partake too heavily in topic 34. "Vision of the Fountain" is composed of 98% of this topic. Befitting for a text focused on unraveling the message a dreamstate is 
conveying. The quite jagged, but strong shift in influence in the 1870ies is caused by Le Fanu, whose main contributing topics 60,12, 51, 70, 65 are heavily affected. Showing how immensly influential 
his voice is to the most prevalent topics of the corpus. 5, 51, 12, 34, 38, 45 show yet another spike around 1898 due to Corelli and Machen. While Machen, like Le Fanu has a very classical profile 
fitting the trend, Corelli is highly unique in her distribution of topics. Dealing with fighting, strife and exploration.



### Based on averaged importance for a wider range of them:

Here very prominent is the focus of Mathew Lewis on Topic 51: Disillusionment with Society, 52: Adventure, Spendor, Power and Challenges, History. 39: Quest for Meaning - Self-Discovery, Transformation,
for Oscar Wilde, 34: Secrets and Suspense - \n Mystery, Devils and Assassinations and 12: Home Invasion - Domestic Mystery and Conflict for John Keats, 14: Conflict, Animosity, and Change - \n Emotional
Changes, Death and Construction. and 69 for Coleridge, 36: Individualism vs. Conformity - \n Rebellion and Social Norms and 52: Adventure, Spendor, Power and Challenges, History for Aikin, 21 for Gilman
and a general heavy reliance on 5: Excitability, Madness, and Deceit, With Walpole carrying the highest values for 5, and Shelly's second ex aequo with Lee Sophia and Reeve Clara.

Generally speaking Topic 5: "Excitability, Madness and Deceit" is a prevalent theme across many authors, reinforcing the idea that Gothic literature frequently explores psychological instability and darker aspects of human behavior. Topic 51: "Disillusionment with Society" appears significant for several authors as well, suggesting themes of resistance against societal norms and the exploration of characters who are at odds with their social context.

Topic 70: "Myth and splendor - Wealth and Castles" is prominent for authors like Charles Maturin, Arthur Machen, and Walpole, and indicates a focus on grandeur, historical settings, and perhaps a reflection on the role of the past in shaping individual identities and social structures. Oscar Wilde's most prevalent topics 52: Adventure, Spendor, Power and Challenges, History and 39: Quest for Meaning - Self-Discovery, Transformation mirror these tendencies of a nostalgic fascination with the past and a drive for self-actualization.

Sleath Eleanor, Parsons Eliza, Lee Sophia, and Reeve Clara have a significant presence of Topic 65: "Atmospheric Battle Descriptions and Royalty", which could reflect their works that delve into grand conflicts and courtship.

For instance, John Keats, Algernon Blackwood, and Bram Stoker have a considerable portion of their bars dedicated to Topic 5: "Excitability, Madness and Deceit" and Topic 12: "Home Invasion - Domestic Mystery and Conflict", suggesting a focus on personal turmoil and the encroachment of danger into personal spaces.


Recurring Topics Across Authors Median Values:

Topic 5: "Excitability, Madness, and Deceit - Aggression, conflict, and glee" seems to be a prevailing theme among almost all authors, indicating that elements of madness, deceit, and emotional extremes,
Topic 51: "Disillusionment with Society - Resistance, Protest, Retreat" is also frequently present, suggesting a common narrative thread where characters grapple with societal norms and often feel a sense of disillusionment, while engaged in uncanny and intimate struggles that rage close to home and yet have a faraway air to them.
Topic 10: "Ferocity and Tragedy - animalistic traits, intimacy, conflict and science.", Topic 12: "Home Invasion - Domestic Mystery and Conflict.",
Topic 70: Myth and splendor - Wealth and Castles.",

Marie Corelli and Nathaniel Hawthorne share a common interest in Topic 29: "Bickering, Fighting and Mountains", which might suggest a thematic focus on interpersonal conflict and possibly the rugged landscapes that are often a backdrop in Gothic tales.

Edgar Allan Poe is unique with Topic 28: "Communion in Nature - Transformation, Relationships and Identity", resonating with Poe's themes of personal transformation, identity, and often a deep connection with the natural world as a setting for his narratives.

Arthur Machen shows a distinct association with Topic 12: "Home Invasion - Domestic Mystery and Conflict", highlighting his interest in the invasion of the domestic sphere by supernatural or mysterious settings, especially befitting his many texts on supernatural boundary transgressions and invaders from other worlds.

Nathaniel Hawthorne:
Distinct Theme: Topic 70: "Myth and Splendor - Wealth and Castles"

Hawthorne’s works often grapple with the moral legacy of Puritanism, and his focus on myths and castles may be seen as an allegory for the grand narratives and moral edifices of his own culture. This theme suggests a preoccupation with the past's weight on the present, reflecting a distinctly American perspective on history, morality, and identity.

Effect: Hawthorne's use of myth and grand settings creates a sense of historical depth and moral complexity, often questioning the possibility of redemption from past sins. His characters are frequently caught between the opulence of tradition and the necessity of moral integrity, exemplified in works like "The House of the Seven Gables."

Edgar Allan Poe:
Distinct Theme: Topic 28: "Communion in Nature - Transformation, Relationships and Identity"

Poe's unique theme reflects his exploration of the individual's psyche and the transformative power of nature. He frequently uses natural settings as a mirror for or a catalyst for internal psychological states.

Effect: Poe’s narratives often lead to moments of epiphany or horror as his characters confront their own identities. Nature in Poe's works is not just a backdrop but an active participant in the narrative, influencing and reflecting the characters' mental and emotional journeys.

Arthur Machen:
Distinct Theme: Topic 12: "Home Invasion - Domestic Mystery and Conflict"

Machen's focus on the invasion of the domestic sphere might hint at his interest in the vulnerability of personal space and the erosion of the boundaries between the safe and the profane.

Effect: This theme often leads to a deep-seated unease, as the sanctity of home is breached by otherworldly forces, making the familiar uncanny. Machen's work could be seen as prefiguring the modern psychological horror genre that frequently uses similar themes.

Marie Corelli:
Distinct Theme: Topic 29: "Bickering, Fighting and Mountains"

Corelli’s narratives weave together interpersonal conflict with dramatic natural landscapes, perhaps reflecting the emotional turmoils and societal upheavals of her time.

Effect: The recurring theme of conflict against the backdrop of imposing nature may symbolize the characters' internal struggles and the larger societal conflicts. Mountains in her work might serve as a metaphor for obstacles to be overcome or as imposing witnesses to human folly.

Sheridan Le Fanu:
Distinct Theme: Topic 5: "Excitability, Madness and Deceit - Aggression, conflict and glee"

Le Fanu’s Gothic tales often revolve around psychological ambiguity and unreliable narrations, with madness and deceit as central elements.

Effect: The focus on madness and deceit creates a pervasive sense of paranoia and questions the nature of reality itself. His stories such as "Carmilla" and "Uncle Silas" often feature characters whose grip on sanity is as tenuous as the reader's understanding of the true narrative.

Bram Stoker:
Distinct Theme: Topic 61: "Vampires, Regality, Experiments, Festivities and Sacrifice"

Stoker, most famous for "Dracula," prominently features themes of vampirism, which intertwine regality and horror, bringing to the fore the anxieties of the fin-de-siècle era regarding degeneration and the breakdown of social norms.

Effect: Stoker’s work creates a contrast between the allure of the aristocratic vampire and the horror of its predatory nature. This theme often explores the fear of the foreign and the taboo, reflecting societal concerns about purity, invasion, and the breakdown of rigid Victorian social structures.


Metaphysical and Philosophical Inquiry Group:
Authors in this group explore themes of existence, the supernatural, and the search for meaning. Topics like Topic 39: "Quest for Meaning - Self-Discovery, Transformation" and Topic 66: "Hidden Knowledge, Learning and Secrets" are significant.
Authors: Le Fanu, Shelley, Wilde, Coleridge and Hogg

Gothic Romanticism Group:
This category includes authors whose works have a strong element of romance intertwined with the Gothic, often exploring the tension between desire and morality. Topics like Topic 28: "Communion in Nature - Transformation, Relationships and Identity" and Topic 44: "Companionship in Times of Trial and Distress" or "Topic 6": "Nature and Reasoning - \n Creativity, Understanding, mixed with Fauna.", are indicative.
Authors: Poe, Kipling, Le Fanu, Hawthorne

Supernatural and Horror Group:
Authors who frequently delve into the supernatural, horror, and the unknown belong here. They explore themes encapsulated by topics such as Topic 61: "Vampires, Regality, Experiments, Festivities, and Sacrifice"
Authors: Stoker, Byron, Stevenson

Social and Political Commentary Group:
These authors use Gothic elements to critique social and political structures. Topics that stand out include Topic 36: "Individualism vs. Conformity - Rebellion and Social Norms" and Topic 51: "Disillusionment with Society - Resistance, Protest, Retreat".
Authors: Hawthorne, Brown, Lytton, Gaskell, Chambers, Ainsworth, Machen, Scott, Lee Vernon, Smith Charlotte, Stoker, Shelly Mary, Radcliff, Blackwood, Wharton, Le Fanu, Corelli share a method of expressing social discontent with the use of topic 51.

Historical and Mythic Reconstruction Group:
Works by these authors are characterized by a strong sense of history and the interweaving of myth within their narratives. Prominent topics are Topic 54: "Medieval Cities, Castles and Courtship" and Topic 70: "Myth and Splendor - Wealth and Castles".
Authors: Radcliffe, Hawthorne, Corelli, Le Fanu, Wharton, Blackwood, Stoker, Lee Vernon, Scott, Machen, Ainsworth, Gaskell

Pioneers of the Psychological Thriller Group:
This grouping is for authors who laid the groundwork for what would become the psychological thriller, focusing on the human mind's complexities and its vulnerabilities. Topics such as Topic 5: "Excitability, Madness and Deceit", Topic 38: "Psychology, Trauma and Secrets"  and "Topic 44": "Companionship in Times of Trial and Distress.", are central.
Authors: Le Fanu, Wharton, Blackwood, Radcliffe, Shelley, Stoker, Smith Charlotte, Bierce, Machen, Chambers

Nature and the Sublime Group:
Authors in this group integrate the natural world deeply into their Gothic narratives, often to evoke feelings of the sublime or to reflect the characters' inner turmoil. Look for topics like Topic 6: "Nature and Reasoning - Creativity and Understanding, mixed with Nature" and Topic 28: "Communion in Nature - Transformation, Relationships and Identity".
Authors: Poe, Shelley, Kipling, Chambers.

Conflict and Societal Restructure Group:
These authors focus on the chaos and order of society, the collapse of old structures, and the struggle for new identities. Topics such as Topic 14: "Conflict, Animosity and Change", Topic 37: "Order and Chaos - Constrained Focus and Unchecked Emotions" and Topic 29: "Bickering, Fighting and Mountains", are highlighted.:
Authors: Bierce, Hawthorne, Marie Corelli, Radcliffe, Smith Charlotte



Excitability, Madness, and Deceit (Topic 5) Influence: 10 or 38
There are noticeable spikes throughout the timeline, with a significant peak at 1800 and 1870. The former encompasses the activities of Radcliff, Shelly, and Lewis as some of the founders of the genre, while the latter is due to Stoker, Le Fanu, Poe (+ Related Topics: Wharton, Blackwood, Radcliffe, Mary Shelley, Smith Charlotte, Bierce, Scott Walter, Machen, Ainsworth, Lytton, Brown)

Myth and Splendor - Wealth and Castles (Topic 70) Influence: 4, 7, 65, 1
There's a particularly high peak around the late 1700s, which could correlate with the Romantic movement's interest in the past and the supernatural as seen in the works of authors like Ann Radcliffe and Hawthorne. The decline post-1800 might indicate a shift toward more realistic or psychological narratives. Others like Corelli, Machen, Ainsworth, and Stoker picked up the theme later again. (+ Related Topics: Poe, Le Fanu, Wharton, Smith Charlotte, Lee Vernon, Lytton, Brown Charles Brockden, )

Disillusionment with Society (Topic 51) Influence: 19
The topic peaks sharply in the early 1800s and again in the early 1900s, possibly reflecting periods of social upheaval and reform, which might be explored in the works of authors such as Radcliffe, Hawthorne, Le Fanu, and Shelley. But also: Corelli, Wharton, Stoker, Scott, Ainsworth, Gaskell

Atmospheric Battle Descriptions and Royalty (Topic 65) Influence: 1, 5, 70
This topic shows a pronounced peak in the early 1800s, aligning with the Napoleonic Wars, which might have influenced Gothic literature's thematic content, as seen in the writings of the era that deal with grand historical events and their aftermath. Relevant for: Le Fanu, Wharton, Smith Charlotte, Lee Vernon, Lytton, Brown Charles Brockden, Stoker (Related Topics: Corelli, Machen, Ainsworth, Le Fanu, Poe)

Home Invasion - Domestic Mystery and Conflict (Topic 12) Influence: 4, 65, 34
The peaks in the early 1800s and early 1900s could reflect societal anxieties about the sanctity of the home and the individual's security during times of social change, a theme evident in the works of Stoker and Le Fanu. (Related Topics: Wharton, Ainsworth)

Ferocity and Tragedy (Topic 10) Influence: 65, 5, 45
The graph shows peaks in the late 1700s and then again in the mid-1800s, which might correspond to periods where themes of primal instincts and the questioning of humanity became prominent, perhaps in response to the Enlightenment and later, the Industrial Revolution. Relevant for Chambers and Brown (Related Topics: Poe, Bierce)

Secrets and Suspense - Mystery, Devils and Assassinations (Topic 34) Influence: 38, 12, 11, 4
There's a notable peak around the 1790s, potentially reflecting the influence of the French Revolution and the rise of Romanticism, with its emphasis on emotion and individual experience, as seen in the works of authors like Radcliffe and Lewis.

Psychology, Trauma, and Secrets (Topic 38) Influence: 10, 17, 15
A steady increase into the 19th century reflects the growing interest in human psychology and the exploration of trauma, possibly influenced by the psychological theories emerging at the time and explored in Gothic fiction by authors like Poe.

Status and Individuality - Striving, Misery and Plentifullness - Excess (Topic 3) Influence: 6, 5, 70
The peak in the late 1700s may be associated with the social upheavals of the time, such as the American and French revolutions, which challenged existing hierarchies and social structures, themes explored in the literature of authors like Hawthorne. (Related Topics: Chambers)

Intimacy, Emotions, and Identity (Topic 45) Influence: 10, 3, 2
The graph shows a steady presence with a few peaks, particularly in the mid-1800s, which could correspond to a focus on personal relationships and the inner self, possibly explored by authors like Charlotte Brontë or Kipling. (Related Topics: Poe, Bierce)


# Attribute based distributions:

## Gender distribution:

It is difficult to pass any judgment on these topics, especially not any readily gender-coded ones, given that they seem to mirror one another in the general content.
Both groupings share a topic related to some form of entertainment, some associations with traveling, some mythical and fantastical associations, and some associations with distress.
Both have topics with associations of romance and emotions. Only a mild difference might be put forth, that the strongly male topics covering emotions have a stronger association with
trials, honor, and courtship offer a more formal and restrained type of interaction. "Companionship in Times of Trial and Distress." encompasses terms like "brood, firmness, accommodate,
acceptance, and conducted equilibrium." those carry more noise at that. Meanwhile the topic "Emotional Dynamics and Interactions" with words like "breathless, hug, vociferating, moan, ruffled, brazen"
has a more immediate, unmediated, and passionate note to them.

While none of these gender-coded ones are among the most defining topics for the whole corpus, "38 - Psychology Traum and Secrets" is prevalent enough to be ranked among the 20 most
influential ones, showing up for Mary Shelly, Charlotte Smith, but also Charles Brockden Brown, Parson Eliza and Edward Bulwer Lyt Lytton as defining elements. Among the most influential texts for this topic,
there are also texts by Ann Radcliffe, Marie Corelli, Lee Sophia, and many other female authors within the corpus.

The same holds for "28 - Communion in Nature - Transformation, Relationships, and Identity", which can be considered the topic of Romanticists and Decadence writers with texts from Poe, Byron, Wilde and
Hawthorne contributed most strongly to them.


## Nationality distribution:

The overwhelming majority of the contributions of distinctly American voices seem to be bound to the strongly masculine topics about poise, but also the one about Romanticism
we had previously uncovered, with an overwhelming influence being Poe, Chambers, Brown, and Hawthorne, even if the most highly associated one of them somehow ranking
"The Tell-Tale-Heart", which quizzically subverts the posed expectations.

The distinctly British voices carry a much stronger weight than any of the other nationalities, with two of them arising from the list of distinctly female topics:
"22 - Emotional Dynamics and Interactions" and "38 - Psychology, Trauma, and Secrets", while 38 has a very dense rate of Mary Shelly and Ann Radcliffe texts,
22 is a very diverse topic in terms of authors contributing to it, but the topic carries a strong heterogeneity concerning nationality.
As mentioned above, it carries with it a lot of strongly passionate vocabularies like "breathless, hug, vociferating, moan, ruffled, brazen" with the highest contribution by Lee Vernon's "Hauntings" or Godwin's "The Adventures of Caleb Williams".



## Sentiment Distribution:

The connection between sentiment and different topics is not particularly strong, but in those cases where it is present the connection seems very natural and intuitive,
with texts that are strongly associated with topics that mark carnage, crime, death and tense judgments being leaning towards a more negative sentiment, while those focusing on self-expression, ambition, intimacy seduction leaning towards a positive sentiment.

But given that only three entries have a higher value than 0,1 the connections are not overly strong to begin with.


### Cluster Analysis:

### PCA and K-Means:
The grouping into clusters shows an even distribution of topics into two groups with a smaller third party that has a much narrower distribution that focuses on a few specific topics, but their narrower focus is concentrated on some that carry exceptional weight on the corpus as a whole: 70 "Myth and splendor - Wealth and Castles" and 12 "Home Invasion - Domestic Mystery and Conflict", with 12 being particularly focused in its influence on a select few influential authors that stand apart:

The importance of 70 might on the other hand reflect its weight on some of the major voices within the corpus, such as Hawthorne and Marie Corelli.

Further important influences to investigate are topics 49 - "Departure and Music", 50 - "Myth, Nature, Wonder and Despair" and to a lesser degree 51 - "Disillusionment with Society - \n Resistance, Protest, Retreat".

A closer inspection is warranted for these sparse clusters with only a few entries for 35 - "Mental Illness, Law and Outcasts - Fear, Suspicion and Struggles", 36 - "Individualism vs. Conformity - Rebellion and Social Norms", 52 - "Adventure, Spendor, Power and Challenges, History" and a lot of weight onto 70, "Myth and splendor - Wealth and Castles".

A subsection of the text seems to be dealing heavily with topics focused on societal retreat, solitude, personal autonomy, and rebellion for the sake of one's convictions. But there seems to be a split within the interpretation of those topics grouping them into one category focused on adventure, exploration, marveling at discoveries, and forgotten splendor. Meanwhile, the other grouping of texts is equally disillusioned and in opposition to or active departure from society, but does not enjoy what it finds and is haunted by foreign forces that bring conflict and grief.

Jacobs's "Monkey's Paw" and Keats's "La Belle Dame sans Merci," both tell a tale of a tempting encounter with an alluring other, a magical artifact and a fairy, and detail the anguish that their wants brought them.

Similarly, Machen's "The House of Souls" is a collection of short texts, the most prominent of them "The Inmost Light" "The Great God Pan"  and "The White People" which deal with humans that cross the veil of what was for their kind to perceive and experience and the disturbing or corrupting experiences that ensued.

Meanwhile Hawthorne's "The Minister's Black Veil” tells the story of a man of faith turning away from life in his community and his old life, only to rise in esteem, influence, and power through his renouncement of personal connection. "Sunday at Home" is an ambiguous text about worship and community and a mixture of longing and contempt for a church congregation.


The outlying texts make up the following:

{1: ['Hawthorne_SundayatHo_1',
  'Jacobs_TheMonkeyS_1',
  'Jacobs_TheMonkeys_1',
  'Keats_LaBelleDam_1'],
 3: ['Aikin_SirBertran_1',
  'Hawthorne_LittleAnni_1',
  'Hawthorne_TheLilysQu_1',
  'Hawthorne_TheMiniste_1',
  'Hawthorne_TheWhiteOl_1'],
 4: ['Bangs_GhostsIHav_1',
  'Bierce_AnOccurren_1',
  'Holcroft_AnnaStIves_1',
  'Lewis_AlonzoTheB_1',
  'Machen_TheHouseof_1',
  'Stagg_TheVampyre_1',
  'Stoker_TheLairOfT_1',
  'unsigned_CountRoder_1']}#





### Hierarchical Clustering:

Here the grouping seems to create two outgroups composed of 31 - "Exploration, Gloom, Caverns", a very niche topic with little weight on the larger whole, and 29 - "Bickering, Fighting and Mountains", a highly concentrated topic with impact on the wider grouping and 60 - "Confession and marriage before  Conscription and Battle" also a very niche topic with little weight to it.

The other outgroup cluster is composed of 65 - "Atmospheric Battle Descriptions and Royalty", 51 - "Disillusionment with Society - Resistance, Protest, Retreat", 5 - "Excitability, Madness and Deceit -  Aggression, conflict and Glee" and 38 - "Psychology, Trauma and Secrets". The latter poses a very powerful group of topics that carry a large weight on the corpus within a small selection.



# Network Analysis:

## Authors influence based on averaged topic distribution:

The network shows a few clear centers of similarity and influence:

1) The biggest collection of influential nodes is a grouping composed of Mary Shelly, William Godwin, Frances Burney, and Charles Brockden Brown, with several smaller authors surrounding them. Their influence and central position is reflected in their topic distribution as well, Brown, Godwin and Shelly represent all the most central and influential topics within the corpus, making them pivotal in shaping the gothic fiction genre. Their central location and the number of connections imply that they could have had a considerable influence on their contemporaries and possibly on those who followed.

2) Another center is composed of Percy Shelly, Horace Walpole, Elenor Sleath, and Thomas Leland. Making for a very early group of authors, all active before 1800, carrying a pioneering position.

3) A smaller and less densely connected grouping covers Sheridan le Fanu, the Bronte sisters, Elizabeth Gaskell and Corelli Marie, whose texts share topics with an emphasis on psychological exploration and internal struggles, potentially influenced by Romanticism.

4) Additional points of interest are, how 1 and 2 are connected through Regina Maria Roche. 2 and 3 are connected through Eaton Stannard Barret, and 1 and 3 through Hogg James and Beckford William.

5) Furthermore noteworthy is the fact that Hawthorne, who was arguably overrepresented in many other graphs, is absent here. By uniqueness of style, idiosyncrasy, or the result of the aggregation of such a broad range of topics. The same goes for Stoker and Ann Radcliffe.




## Network of texts based on averaged topic distribution:

Taking the length of texts and the number of contributions out of the picture, but potentially also lessening the weight an individual unique piece a contribution might carry, the averaged distribution shows a slightly different picture.

This network has many similarities with the previous one:

1) It moves Godwin's Caleb Williams into a centerpiece position connecting the first and the second group, while the works of Mary Shelly drift into the centers of all the major groupings. Pieces from Le Fanu, Gaskell, Shelly, and Lewis intermix with Roche's The Children of the Abby carrying particularly much weight and Brown's Edgard Huntly and Arthus Mervyn and DeQuincey's Klosterheim in a mix.

2) Firmly grouping Walpole, Percy Shelly, Elenore Sleath, and Thomas Leland in a shared circle of influence, and it shifts Mary Shelly's Frankenstein also into this cluster, with Eaton Barrett's The Heroine as a new outer centerpiece carrying a lot of traction. Here finally the figure of Ann Radcliffe emerges, positioning here centrally within the early pioneers of the genre.

3) The third smaller hub has largely fractured and has gotten reabsorbed, leaving Francis Burney's Carmilla as a centerpiece with some others, like Richard Burton's Vikram, Mary Shelly's Lodore, Brown's Wieland around him, but there are fewer circulating in its orbit.

4) At the outskirts of this orbit Machen and Blackwood have united again, as opposed to the other display, with Godwin's St. Leon and Carver's Horror of Oakendale connecting them with the circles of the third branch. Once again, Hoggs connects groups 2 and 3, but Beckford is absent and in his stead, Lytton and Polidori have shifted. This highlights the crystallization of a cluster of texts surrounding the intrusion of outsiders and forbidden knowledge.

5) Hawthorne's works appear on the fringes of the network disconnected from most other pieces, mainly self-referential. Stoker and Byron are largely absent as well, influencing most of all each other.

This grouping puts more emphasis on Mary Shelly and Willaim Godwin as a thematic bridge between different groupings of Gothic fiction authors, highlighting their thematic sway over the genre formation as a whole.




# Network Graph on Textual Influence Through out time:


This grouping, which takes chronology into consideration, brings a few previously unheard of texts to the forefront, but the larger picture strengthens the impression informed by previous network analysis. The fact that the labeling has been done in order of degree centrality allows for a more precise ranking than any of the previous attempts and takes the element of personal expectation, preferential investigation and subjective gaze out of the picture.

The shape of the network has drastically changed in comparison to the previous iterations providing one larger, loosely integrated cluster consisting of a number of sub groupings, as well as a scant few highly influential outliers which seemingly arose without reference to prior works of the genre, which nevertheless provided a rich source of inspiration for subsequent texts.

Upper Outliers:

22: Edward Bulwer-Lytton's Falkland: An amoral piece of self-indulgence centered around the courting of a young woman by a protagonist tormented by premonitions of her death — inspired by the Sturm and Drang Goethe piece Sorrows of Young Werther.

69: Mary Shelly's The Fortunes Of Perkin Warbeck: The Fortunes of Perkin Warbeck is a piece of political intrigue set in the War of the Roses.

24: Mathew Lewis' The Castle Spectre: The text covers religious fanaticism and psychological mystery.

44: Walter Scott's The Black Dwarf: The Black Dwarf details the story of a misanthropic hermit dwarf in league with the devil amid political intrigue.

39: Edgar Allan Poe's The Fall of the House of Usher: The Fall of the House of Usher details the story of an isolated aristocratic family, madness, as well as feelings of fear, doom, and guilt.

40: Charles Dickens' The Haunted Man and the Ghost's Bargain: The text deals with a professor haunted by past mistakes and sorrows plagued by apparitions.

41: Elizabeth Gaskell's The Doom of the Griffiths: It covers family curses, myth, revenge, murder, and the role of women in society.


Upper Half:

38: Mary Shelley's The Last Man: It deals with isolation, global plague, disaster, medicine, science, and the loss of political ideas. 

29: John Palmer's The Haunted Cavern. A Caledonian Tale: The Haunted Cavern covers specters, murder, gloomy caverns and a betrothal to a villain. 

32: Eaton Barrett's The Heroine: A popular bestseller that combined the style of Radcliffe's gothic romances with an over the top comedic and quixotic adventure and exploration arc of a female protagonist, with a paternal call or domestic submissiveness at the end. This text had already appeared highly influential in the visualizations above, and numerous quotes on its reach and influence exist.

77: Charlotte Smith's The Emigrants: Emigrants deals with the trauma and alienation French emigrants after the revolution carry with them. 



Upper Half Lower:
42 + 36 + 53: Nathaniel Hawthorne's The Lily's Quest and The White Old Maid and Little Annie's Ramble: All three Hawthorne texts stem from the same collection of short stories. The Lily's Quest, deals with the cycle of life and death, the futility of the pursuit of happiness and the necessity of hardship. The White Old Maid deals with ominous ritual surrounding death, a love triangle and reunification. Little Annie's Ramble covers childhood innocence, curiosity, and the longing of an adult for simple joys past, benevolent unconsenting child abduction.

58: William Ainsworth's Rookwood: A gothic romance detailing royal inheritance disputes after an ill-fated death.




Lower Outliers:

19: Wilkie Collin's The Woman in White: Collin's most highly esteemed piece of Sensationalist mystery fiction about the dispossession of a disenfranchised noblewoman accused of lunacy. 

28: Montague James' Ghost Stories of an Antiquary: Deals with the veiled invasion of outside forces in the rural retreat of a scholar. (reminiscent of Sheridan or Machen)

52: Marcus Clark's For the Term of his Natural Life: It deals with the cruelty and systematic violence inflicted on a wrongfully convicted.

33: Algernon Blackwood's The Willows: Supernatural, threatening surroundings, intense dread and anxiety. (Strong influence on 20th-century weird fiction)

34: Richard Francis Burton's Vikram: An Indian tale of the hunt for a necromantic vampire.



Bottom Half Up:

13: William Godwin's St. Leon: Godwin grapples with fallen nobility, madness, Faustian bargains, and a retreat from society in despair.

45: Mary Shelley's Lodore: Lodore covers power, responsibility, and the role of women within a family structure. 

31: AM Bernard's The Abbot's Ghost: The Abbots Ghost is a tale of intrigue, ghost, forbidden love, and miracles.

23: Jane Austin's Northanger Abbey: A famous satire on Gothic Romance, with a too-romantic girl and a frightening backdrop.

30: Ann Radcliffe's A Sicilian Romance: Its themes are fallen nobility, shameful secrets, and psychological terror in a fallen castle.


Bottom Half Upper:
20: Percy Shelley's Zastrozzi:  A piece lauded for its depiction of amoral self-indulgence and individualism within a backdrop of a gothic setting.

17: Reeve Sophia's The Mysterious Wanderer: A gothic romance in the style of Radcliffe, rich with deceit, murder, and family tragedy.

47: William Beckford's Caliph Vathek: Caliph Vathek is an orientalist tale dealing with ambition, greed, pacts with the devil, and the consequences of unbridled desire.


Center Bottom Right:

25: Arthur Machen's The Great God Pan: The Great God Pan deals with a metaphysical and moral transgression meddling with higher forces that create a corrupted, daemonic femme fatale.

6: Charles Brockden Brown's Wieland: Wieland deals with madness, religious fanaticism, psychological turmoil, and supernatural gruesome violence (early American transposition of the genre after Godwin).

74: Mathew Lewis' The Monk: The Monk details the corruption of a monk by a demon in female disguise as well as romance, temptation, innocence, sexuality, and strong horror elements.

18: Mrs. Carver The Horrors Of Oakendale Abbey: haunted abbey, sensationalist, necromancy, body snatchers, death and decay, grotesque — very popular in its day.



Dead Center:

35: Eliza Fenwick' Secrecy: Female Friendship, hidden pregnancies and betrayal, societal constraints, and punishments.

2: Frances Burney's Camilla: Camilla is a generational tale of coming to age, romance, comedy, and morals with comedic and gothic episodes - immensely popular in its time, endorsed by Jane Austin. 

9: Sophia Lee's The Recess, Or A Tale Of Other Times: political intrigue, heroic female lead, seafaring, warfare, gothic castles, marriage — very popular.

10: Charlotte Smith's Emmeline, Or The Orphan Of The Castle: A Cinderella story of female emancipation, gaining property and standing, where ownership over masonry and bodily autonomy blend. Gothic in style.

27: the anonymous Count Roderic's Castle: Love, birthrights, barbarous, violent rulers, and ominous castles with vengeful specters and dungeons.

37: Ann Radcliffe's The Castles Of Athlin And Dunbayne: The Castles of Athlin and Dunbayne deals with murder, revenge, royalty, sublime nature, excited feelings, gloomy castles, romance, and heroic women.




Center Left:

12 + 8: Charles Brockden Brown's Arthur Mervyn and Edgar Huntly by the same author: Arthur Mervin details yellow fever plagues, crime, theft, plantation work, prostitution, and a morally gray protagonist. Edgar Huntly deals with wilderness anxiety, supernatural, darkness, and fear, sleepwalking, and veiled truths. Both are considered influential early American gothic texts.

4: Ann Radcliffe's The Romance Of The Forest: Adding a discussion or moral values to a tale of horror and suspense, natural sublime and beauty, sexuality. (By contemporaries regarded it as her best)

5: Horace Walpole's The Castle of Otranto: Medieval haunted Castle, supernatural horrific happenings, violence, surprising humor, sexual and grappling with questions of identity (retrospectively one of the earliest and most formative exemplary of the genre)

15: Thomas Leland's Longsword, Earl Of Salisbury: Gloomy settings, evil clergymen, historical basis, abductions, royalty, shipwrecks. (an early cornerstone of the genre)

7: Eleanor Sleath's The Orphan Of The Rhine: picturesque, strongly radcliffeque, scoundrels and half ruined castles, strong emotions, romance, terror (praised by Jane Austen in Northanger Abbey)

21: Ann Radcliffe's The Mysteries Of Udolpho: Forced marriage, foreboding castles, fear, and scheming relatives, heroic idealistic women.




Center Top Right:

1: Regina Maria Roche's The Children Of The Abbey: The Children Of The Abbey was one of the best-selling novels of the 19th century and deals with wicked relatives, a quest for inheritance, love, royalty, castles, and heightened emotions, full of languishing. 

3 William Godwin's Caleb Williams; Or, Things as They Are: A tale of treachery, persecution, political oppression, corrupt hierarchies, psychological obsession, and a big influence on Frankenstein. Individualism and the constraints of institutions.

11: Tobias Smollett's The Adventures Of Ferdinand Count Fathom: Chronicles the travels of a villainous, deceitful dandy with a supernatural undercurrent.

26: Eliza Parsons' The Castle Of Wolfenbach: The castle of Wolfenbach is an important early piece predating many Radcliff texts, lauded by Jane Austin as essential. (early outlier) A gothic royal romance with abundant frenzied expressions of emotion, fainting, weeping, and struggles of identity formation.

14: James Hogg's The Private Memoirs And Confessions Of A Justified Sinner: It deals with a caste haunted by a young woman wrongfully accused of murder.

16: Clara Reeve's The Old English Baron: An homage to Walpoles Castle of Otranto, but intended as a more realistic and streamlined Gothic template — widely adopted. Horror, mystery, ghost stories on castles.




## Feature Evaluation Grouping:

Upper Outliers:

These texts stand out for their unique focus. They might explore themes like psychological horror (Fall of the House of Usher), political intrigue (The Fortunes of Perkin Warbeck), or the supernatural with a dark twist (The Black Dwarf).
---------------------------
The upper outliers consist of works that uniquely combine Gothic elements with other themes such as political intrigue, personal torment, and moral ambiguity. These texts stand apart due to their distinct narrative focuses or thematic explorations that diverge from more central Gothic conventions.

Themes of Amorality and Self-Indulgence: Edward Bulwer-Lytton's Falkland and Charles Dickens' The Haunted Man and the Ghost's Bargain highlight personal struggles with morality and the past, emphasizing the psychological over the supernatural.
Political Intrigue and Historical Settings: The Fortunes Of Perkin Warbeck by Mary Shelley and The Black Dwarf by Walter Scott integrate Gothic elements into historical and political narratives, showcasing the genre's versatility.
Religious Fanaticism and Psychological Mystery: The Castle Spectre and The Fall of the House of Usher delve into the darker aspects of human psychology against a backdrop of religious extremism or decaying aristocracy.
-------------------------------
-> Psychological Terror, Politics, Fanatism, Transgressive Indulgence and Moral Debasement

Upper Half:

These stories deal with isolation, societal issues, and supernatural elements. We see themes of plague and disaster (The Last Man), female experience and societal expectations (The Heroine, The Emigrants), and classic gothic tropes like haunted caverns and gloomy settings (The Haunted Cavern).
-----------------------------------
This cluster embodies texts that, while still retaining core Gothic elements, begin to incorporate broader themes such as global catastrophes, scientific exploration, and societal alienation.

Global Plague and Isolation: Mary Shelley's The Last Man is a prescient narrative of global disaster, emphasizing isolation and the loss of societal structures, a theme resonant with contemporary concerns about pandemics and societal collapse.
Comedic Overtones and Domestic Submissiveness: Eaton Barrett's The Heroine challenges Gothic conventions with humor and satire, reflecting on the genre's tropes with a comedic twist.
Trauma and Alienation: The Emigrants by Charlotte Smith explores the emotional and societal impacts of displacement, offering a nuanced examination of trauma and alienation in the post-revolutionary context.
----------------------------------
-> Societal Dissarray and Alienation, Humorous Subversion of Expectations 


Upper Half Lower:

These are all by Nathaniel Hawthorne and explore interconnected themes. They might delve into the cycle of life and death (The Lily's Quest), dark rituals and family secrets (The White Old Maid), or childhood innocence and loss (Little Annie's Ramble).
-------------------------------------
This subset features texts that start blending traditional Gothic themes with explorations of life cycles, the pursuit of happiness, and the innocence of childhood, suggesting a transition towards more introspective and philosophical themes.

Life, Death, and Pursuit of Happiness: Nathaniel Hawthorne's stories from the same collection explore existential themes through the lens of Gothic fiction, juxtaposing life's transience against the backdrop of 
traditional Gothic settings.
------------------------------------
-> Life, Death, Pursuit of Happiness


Lower Outliers (Similar to Upper Outliers):

These stand out for their specific themes. The Woman in White explores social injustice, Ghost Stories of an Antiquary deals with unsettling encounters in rural settings, For the Term of his Natural Life focuses on institutional cruelty, and Vikram dives into the world of the supernatural with a vampire tale.
--------------------------------------
The lower outliers are distinguished by their exploration of sensationalism, mystery, and the supernatural, with a strong focus on systemic violence, supernatural dread, and psychological horror.

Sensationalist Mystery and Supernatural Dread: Texts like The Woman in White and The Willows focus on disenfranchisement, systemic cruelty, and the overwhelming power of nature, offering a stark portrayal of human and supernatural antagonism.
---------------------------------------
-> Systemic violence, Supernatural Othering Encounters


Bottom Half Up and Bottom Half Upper:

These clusters focus on themes of nobility, madness, Faustian bargains, and the satire of Gothic conventions, illustrating the genre's ability to critique social norms and explore the complexities of human desire and fear.
Fallen Nobility and Satire: Works like William Godwin's St. Leon and Jane Austin's Northanger Abbey engage with the disillusionment with nobility and the parody of Gothic tropes, respectively, showcasing the genre's adaptability and critical edge.
-------------------------------------------
Bottom Half Up:
These texts explore classic gothic themes like fallen nobility, psychological terror, and forbidden love. We see stories of characters grappling with despair (St. Leon), strong female leads in family dramas (Lodore), and intrigue set in gothic settings (The Abbot's Ghost, Northanger Abbey, A Sicilian Romance).

Bottom Half Upper:
Here, the focus might be on dark desires and consequences. We see exploration of amorality and individualism (Zastrozzi), gothic romances with family tragedies (The Mysterious Wanderer), and cautionary tales of ambition and demonic pacts (Caliph Vathek).
--------------------------------------------
Bottom Half Up:
-> Fallen Nobility, Emotional Distress and Struggles of Love, Satire

Bottom Half Upper:
-> Dark Desires and Dire Consequences, Pacts




Center Bottom Right, Dead Center, and Center Left:
Central clusters highlight the genre's core themes, such as the struggle with identity, morality, and the supernatural. These texts, including The Great God Pan, Camilla, and Arthur Mervyn, embody the Gothic tradition's exploration of moral ambiguity, societal constraints, and the supernatural.
----------------------------------------------------
Center Bottom Right:


Dead Center:
These all share elements of gothic settings and themes, with a focus on female characters. We see stories of hidden pregnancies and betrayals (Secrecy), gothic romance with a focus on inheritance (The Recess), female empowerment through property ownership (Emmeline), and classic gothic tropes of castles, vengeful spirits, and royalty (Count Roderic's Castle, The Castles of Athlin and Dunbayne).

Center Left:
These are American gothic tales with distinct themes. Arthur Mervyn tackles social issues like yellow fever and moral ambiguity, while Edgar Huntly explores wilderness anxieties and the supernatural. We also see foundational gothic texts with themes of terror, suspense, and the sublime (The Romance of the Forest, The Castle of Otranto, Longsword, Earl of Salisbury, The Orphan of the Rhine, The Mysteries of Udolpho).
-----------------------------------------------------
Center Bottom Right:
-> Very grotesque, physical depictions in religously coded settings, preceded by moral transgressions (Body Horror)

Dead Center:
-> Female Protagonists, struggling for control, their place in a changing environment or love (Gothic Romance)


Center Left:
-> Core foundational early British texts and their first adaptations over sea. The latter grapple with disease and the wilderness, while the former establish core themes of hightened emotions, insanity, the sublime, ghosts and castles


Center Top Right:

Here, the focus might be on family secrets, gothic settings, and societal power structures. We see stories of wicked relatives and inheritance quests (The Children of the Abbey), political intrigue and social commentary (Caleb Williams), chronicles of a villain (The Adventures of Ferdinand Count Fathom), early gothic romance (The Castle of Wolfenbach), and a haunted family saga (The Private Memoirs and Confessions of a Justified Sinner).
------------------------------------------------
This area of the graph highlights the intersection of Gothic fiction with themes of inheritance, identity, and the quest for understanding, represented by texts like The Children Of The Abbey and Caleb Williams. These works explore the individual's place within societal and familial structures, often against a backdrop of mystery and intrigue.
-----------------------------------------------
-> These texts deal with unrest within power structures, weather through family intrigue, religous power struggles or a quest of individuals against corrupt institutions




-----------------------------------------------
-----------------------------------------------
-----------------------------------------------


# Central topics reoccuring in the core nodes:

1. Haunted Castles and Supernatural Horror: This cluster includes novels with a focus on haunted castles, supernatural events, spectral apparitions, and unexplained phenomena. Examples are "The Castle of Otranto," "The Mysteries of 
Udolpho," and "The Orphan of the Rhine."
2. Gothic Romance: This cluster features novels that revolve around romantic relationships set against a gothic backdrop. Castles, intrigue, scheming relatives, and heroic women are prominent features. Examples include "The Children 
of the Abbey," "The Mysteries of Udolpho," and "The Castle of Wolfenbach."
3. Quest for Identity and Inheritance: These novels involve protagonists who embark on a journey to discover their true identity or inheritance. Supernatural elements, mystery, and psychological obsession are common. Examples are 
"Arthur Mervyn" and "Edgar Huntly," both by Charles Brockden Brown.
4. Historical Gothic: This cluster includes novels that are rooted in historical events and feature a gothic atmosphere. Abductions, royalty, shipwrecks, and gloomy settings are typical elements. Examples include "Longsword, Earl of 
Salisbury," by Thomas Leland, and "The Romance of the Forest" by Ann Radcliffe.
5. Morality Tales: These novels blend horror, suspense, and a discussion or moral values. Natural sublime and beauty, sexuality, and questions of identity are addressed in these stories. Examples include "The Castle of Otranto," by 
Horace Walpole, and "The Romance of the Forest," both by Ann Radcliffe.
6. Early American Gothic: This group includes influential early American gothic texts that deal with themes like yellow fever plagues, crime, theft, plantation work, prostitution, and a morally gray protagonist. Examples are "Arthur 
Mervyn" and "Edgar Huntly," both by Charles Brockden Brown.
7. Darkness, Fear, and Veiled Truths: These novels explore themes of wilderness anxiety, supernatural, darkness, and fear, with veiled truths and surprising discoveries. Examples include "The Adventures of Ferdinand Count Fathom" by 
Tobias Smollett and "The Castle of Wolfenbach" by Eliza Parsons.
8. Morally Gray Protagonists: These novels feature morally gray protagonists dealing with a variety of issues, including plagues, crime, theft, plantation work, and prostitution. Examples include "Arthur Mervyn" and "Edgar Huntly," 
both by Charles Brockden Brown.

----------------------------------------------------------------------------------------------------------



## Contextual Comparison:

While the comparisons on the level of influential topics and authorial contribution to a given topic put more emphasis on the uniqueness of certain voices towards a specific theme and association put a lot of focus on authors with a succinctly unique voice that carried a wide reach, such as Poe, Le Fanu, Stoker and Hawthorne, The network analysis showed that while their contributions were influential and formative for a certain aesthetic, they did not invite the same kind of imitation and formation of a movement as such as the likes of Walpole, Leiland, Brown, Sleathe. In the topical part of the analysis, Walpole voice was not represented in the topical part of the analysis, while his influence carried exceedingly far on the level of textual similarity at the start of a movement. Influential and formative, yet not distinct in the same manner. The influential, exceptional voices which combined both analyses are Godwin, Mary Shelly and to a lesser degree Ann Radcliffe.




## Evaluation of the alternative model's suitability for these purposes, as well as the plausibility of the LDA distribution: 

The Contextual Topic Model (CTM) seems to be unsuitable to the Shannon divergence based multidimensional scaling employed by pyLDAvis, the topics seem coherent and the overall distribution throughout time roughly analogous to that of the LDA used in the analysis, strengthening the impression that the topic patterns and their distribution is static and driven both by the distribution of publications throughout the decades, and shifts in relevant themes.

The principal component analysis based on its topic distribution shows a more evenly spread out shape, but a roughly analogous amount of spread, strengthening the overall picture that both of them present in their plausibility.

The results of the topic modeling in embedding space (ETM) on the other hand seem uninterpretable and fundamental, at odds with those of the other two. While both CTM and ETM are not interpretable with the same multidimensional scaling techniques and both provide meaningful topics, the features of the ETM do not provide any meaningful spread throughout time or across texts, leading to both an uninterpretable historical distribution, and principal component analysis.
