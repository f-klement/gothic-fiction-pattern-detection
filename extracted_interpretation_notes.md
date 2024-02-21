# Collected Notes on the Interpretation of the Analysis on the gothic fiction corpus:

Some of the element are in order of their occurence within the notebook, others are rearranged contextually,
but generally speaking are not provided with a full description of the setting they were taken out of there.
This is still to come, ut n terms of content the bservations and groupings should be a to stand on their own 
and speak for themselves on what aspect of the corpus, the topic model or the relationship between the authors
within them they address. This is primarily still a collection of thoughts - mental lint in the dryer that
is life. 


## Topics:

topic_labels = {
    "Topic 1": "Ominous Atmosphere - \n Spacial and Auditory Imagery: \n vastness, archaic, Refinement, Gloom, demons.",
    "Topic 2": "Emotional Dialogue -  \n Fear, Secrecy, Flattery,Arousal and Strife \n - Religion and Devils.",
    "Topic 3": "Status and Individuality - \n Striving, Misery and Plentifullness - Excess.",
    "Topic 4": "Myths, Trials and Death - \n Persecution of Crime, Telling Tales, magic and ants.",
    "Topic 5": "Excitablity, Madness and Deceit - \n Aggression, conflict and glee.",
    "Topic 6": "Nature and Reasoning - \n Creativity, Understanding, mixed with Fauna.",
    "Topic 7": "Social Pleasantries - \n Diplomacy, Plotting to Gossip.",
    "Topic 8": "Faith, Convictions, Chivalry and Death - \n Erudition, Religion and Knights. Ants.",
    "Topic 9": "Fortitude, Conviction and Adventure - \n Danger and social Station.",
    "Topic 10": "Ferrocity and Tragedy - \n animalistic traits, intimacy, conflict and science.",
    "Topic 11": "Ravens and Gloom - Longing, Death and Artifice.",
    "Topic 12": "Home Invasion - Domestic Mystery and Conflict.",
    "Topic 13": "Rituals and Festivities - \n Dance, Witchcraft and Coronations.",
    "Topic 14": "Conflict, Animosity and Change - \n Emotional Changes, Death and Construction.",
    "Topic 15": "Trickery and Science - \n Deceit, Reasoning and Institutions.",
    "Topic 16": "Desecrated Chapel - \n Confessions and Defilement - Devils and Maniacs.",
    "Topic 17": "(Un-)death, spectral bodies and judgement - \n human physicality, grief, emotions.",
    "Topic 18": "Mystery and Adversity - \n Dream and fugue states, Investigation.",
    "Topic 19": "Forlorn Carnival - Dances, Disgust and Intimacy.",
    "Topic 20": "Science, Reasoning and Objects - \n Technology, Professions and Nature.",
    "Topic 21": "War, Punishment and Exploration.",
    "Topic 22": "Emotional Dynamics and Interactions.",
    "Topic 23": "War, dreams and demons.",
    "Topic 24": "Human Interactions and Emotional States.",
    "Topic 25": "Flattery, clothing, Interactions.",
    "Topic 26": "Witchcraft, Rituals and Fear of it - \n Banishment, Threats and Armor.",
    "Topic 27": "Dragon Attack and Defense - \n Troops, Mountains and Cynicism.",
    "Topic 28": "Communion in Nature - \n Transformation, Relationships and Identity.",
    "Topic 29": "Bickering, Fighting and Mountains.",
    "Topic 30": "Bureaucracy, Bargaining and Dissatisfaction.",
    "Topic 31": "Exploration, Gloom, Caverns.",
    "Topic 32": "Tranquility and Bustle - \n Terms of Relaxation, Calm and Action.",
    "Topic 33": "Treacherous Company - on the run and scarred.",
    "Topic 34": "Secrets and Suspense - \n Mystery, Devils and Assasinations.",
    "Topic 35": "Mental Illness, Law and Outcasts - \n Fear, Suspicion and Struggles.",
    "Topic 36": "Individualism vs. Conformity - \n Rebellion and Social Norms.",
    "Topic 37": "Order and Chaos - \n Constrained Focus and Unchecked Emotions.",
    "Topic 38": "Psychology, Trauma and Secrets.",
    "Topic 39": "Quest for Meaning - Self-Discovery, Transformation.",
    "Topic 40": "Ambition and Struggle - Emotional Turmoil.",
    "Topic 41": "Despair, Isolation and Oppression.",
    "Topic 42": "Illusion, Enchantment and Betrayal.",
    "Topic 43": "Woodlands, Mystery, Illusion, Beasts.",
    "Topic 44": "Companionship in Times of Trial and Distress.",
    "Topic 45": "Intimacy, Emotions and Identity.",
    "Topic 46": "Frustration, Society, Retreat into Nature - \n Society, Reason, Tension, negative Feelings, Forrests.",
    "Topic 47": "Human Nature and the Connection to the Land, \n Myth and (Human) Nature - Solace, Inspiration, Acceptance for Hardships.",
    "Topic 48": "Enthralling Garden full of Voices - \n Echantment and Vocalization, Nature.",
    "Topic 49": "Departure and Music.",
    "Topic 50": "Myth, Nature, Wonder and Despair.",
    "Topic 51": "Dissilusionment with Society - \n Resistance, Protest, Retreat.",
    "Topic 52": "Adventure, Spendor, Power and Challenges, History.",
    "Topic 53": "Mercantile and Creativity - Haggling and Emotions.",
    "Topic 54": "Medieval Cities, Castles and Courtship.",
    "Topic 55": "Crocodiles, Massacres and Traveling.",
    "Topic 56": "Exploration of an Island and Obsession.",
    "Topic 57": "Carnage near a Castle.",
    "Topic 58": "Weddings and Rituals - Clamoring Throng.",
    "Topic 59": "Judgment and Scrutiny - Tense Diplomacy.",
    "Topic 60": "Confession and marriage before  \n Conscription and Battle.",
    "Topic 61": "Vapires, Ragality, Experiments, \n Festivities and Sacrifice.",
    "Topic 62": "Dragons, Subterraneous Lairs, Riddles and Lore.",
    "Topic 63": "Hidden Dangers, Fear, Anticipation, Supernatural.",
    "Topic 64": "Artistic Ambition and Trials - Mastery and the Devil.",
    "Topic 65": "Atmospheric Battle Descriptions and Royalty.",
    "Topic 66": "Hidden Knowledge, Learning and Secrets.",
    "Topic 67": "Monsters, Art, Romance - Myth and Gloom.",
    "Topic 68": "Secluded Initiation Rites.",
    "Topic 69": "Seduction, Deception, Violence, Bureaucracy.",
    "Topic 70": "Myth and splendor - Wealth and Castles.",
    "Topic 71": "Haunted Castles and their Prohecies.",
    "Topic 72": "Festivities, Noise, Crowds.",
    "Topic 73": "Camps, Trenches and Weather."
}


## Broad Categorization:

Generally speaking the topics can be categrized in a set of main groups: 

-Emotional turmoil and psychologicla distress
-Physical violence and combat
-Social settings, diplomacy and court
-Self expression and frustration with society
-Myth, lore and tales
-Forbidden truths and knowledge
-Adventure and exploration
-Ambition, greed and regality
-Deceit and aprehension
-Science and reasoning
-Nature - woods, mountains and harbors
-Religion and sacred rituals
-Monsters, demons and undead
-Medieval settings, cities and castles
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

8 - 9, 13 - Faith, Knightood and Knowledge

9 - 8, 16, 65 - Conviction and Adventure

10 - 65, 5, 45 - Intimacy and Conflict, Tragedy

11 - 17, 1, 34 - Doom & Gloom

12 - 4, 65, 34  - Home Invasion

13 - 4, 16, 19 - Rituals, Dance, Magic

14 - 5, 65, 17 - Conflict, Death

15 - 7, 5 - Trickery and Science

16 - 9, 13 - Desecrated Chapel

17 - 4, 11, 14 - Undead, judgement and grief

18 - 4, 17  - Mystery and Adversity

19 - 10, 51, 13  - Forlorn Carnival

20 - 6, 8 - Science and Nature

34 - 38, 12, 11, 4 - Secrets, mystery, Suspense

38 - 10, 17, 15  - Psychology, Trauma, Secrets

45 - 10, 3, 2 - Intimacy, Emotions, Identity

51 - 19  - Dissilusionment with Society

65 - 1, 5, 70 - Battle, Atmosphere, Royalts

70 - 4, 7, 65, 1 - Myth, Wealth, Castles



## Strongest Topic Associations:

Henry James Archaic Atmosphere (1)

Wharton -> Gloom and Longing, Blashphemy, Battles & Nature  (11, 16, 65, 6)

Walter Scott -> Gloom and Longing (11)

Corell Marry -> Emotions, Status, Convictions, Institutions, medieval, Mystery,Dances, Social Discontent (2, 3, 8, 15, 18,19, 51)

Radcliffe ->  Emotions, Confict, Madness, Social Discontent (2, 5, 14, 51)

Poe -> Gossip, Gloom,Undead, Mystery, Animals (4, 7, 9, 10, 17)

Bierce Ambrose -> Ferrocious Tragedy (10)

Le Fan -> Madness & Romanticism, Longing, repulsive Intimacy, archaic atmosphere (5, 6, 11, 19, 70, 45)

Blackwood -> Madness, Adventure, Conviction, Dreams and Mystery, Societal Discontent, Identity (5, 9, 18, 51, 45)

Wilde -> Conviction & Death (8)

Keats -> Home Invasion & Mystery and Conflict (12)

Lee Vernon -> Social Pleasantries and Scheming (7)

Stoker -> Home Invasion, Desecration, Dreams & Mystery, Castles & Myth (16, 12, 18, 70)

Hawthorne -> Home Invasion, Witchcraft, Status & Individuality, Deceit & Institutions, Mystery, Meriment (3, 12, 13, 15, 16, 18, 19, 70, 65)

Rymer, James -> Rituals (13)

Coderidge -> COnflict, Emotions (14)

Machen -> Undead (17)

La Spina Grey -> Festivities, Intimacy and Disgust (19) 

Kippling -> Battles & Royalty (65)

Byron -> Intimacy & Identity (45)

Smith Charlotte -> (38)

Shelley Mary -> Psychological Trauma, Madness & Aggression, Trickery and Science, Science & Animalistic Violence (15,10, 38, 5)

Colderidge -> Secrets and Demons (34)

Brown Charles Brockden -> Psychological Trauma (38)



## Textual Associations:

Wharton -> Frightful Dialogue, Myth and Trials, Chivalry & Faith, Rituals & Magic (2,4, 8, 13)

Walpole -> Aggression & Madness (5)

Kippling -> Chivalry & Faith (8)

Shelly Marry -> Gloom, Doom and Longing (11)

Vernon Lee -> Undeath & Grief (17)

Hawthorne -> Myth, Wealth and Castles has three entries by Hawthorne - prime contributer (70) !!!

Moore Thomas -> Intimacy, Identity and Emotions (45)

Parson, Eliza -> Psychological Trauma (38)

Lytton -> Psychological Trauma (38)





# Timeline of the distribution of the most prominent topics and their relevance for the most prominent authors:



Both the selection of topics based on a minimum fluctuation in their importance and the grouping based on them crossing a base threshhold return a similar picture,
putting emphasis on 8 different topics and their distributution through out time. What is clearly visible here is that the three peaks in textual representation,
around 1800, 1830 and around 1900, are in part reflected in the rise of specific topics. Topics 3, 36 and 52 peak prior to 1800 and then fade out of importance,
5 peaks early, declines to a moderate degree until 1830 and then remains as a constant undercurrent. 70 on the other hand rises to prominence early, falls out 
of use, rises very strongly at 1830 becoming a predominant influence and to a lesser degree at 1860, remaining a stable baseline through out as well. 51 and 65 
reach a very decisive peak at 1800 and a second at 1860 and 1880 respectively. 4 only shows two peaks, one smaller at 1830 and a large spike  at around 1850.

This selection offers a clear cut through most all of the central motifs of the genre.


Topic 3: Status and Individuality - Striving, Misery and Plentifulness - Excess.

Peaks in the early 1760s, mid-1780s, and early 1800s, suggesting that themes of personal ambition and the consequences of excess were particularly salient during these times. 
This could reflect societal concerns about the individual's place in a rapidly changing social order in the underlying literature.

Topic 4: Myths, Trials and Death - Persecution of Crime, Telling Tales, magic, and ants.

Shows consistent presence across the timeline with notable peaks in the late 1770s and mid-1850s. Indicating peaks in the  preoccupation with justice, mortality, and the supernatural.

Topic 5: Excitability, Madness and Deceit - Aggression, conflict and glee.

Exhibits spikes around the 1790s and then again in the 1830s. This period coincides with historical events like the French Revolution, the early onset of urbanization and industrialization 
reflecting the tumultuous nature of the times.

Topic 36: Individualism vs. Conformity - Rebellion and Social Norms.

There's an interesting surge in the early 1790s, a sentiment  that is concurrently explored by the Romantic thinkers, some of them overlapping with the authros of Gothic novels.

Topic 51 & 52: Disillusionment with Society - Resistance, Protest, Retreat. Adventure, Splendor, Power and Challenges, History.

These topics seem to rise and fall in tandem at several points (e.g., 1780s and 1840s), suggesting that tales of adventure and power struggles were often accompanied by themes of societal disillusionment.

Topic 65: Atmospheric Battle Descriptions and Royalty.

Shows a peak around 1810, concurrent with the Napoleonic Wars', while the recontextualization into medieval settings of any vivid battle scenes and discussions of royalty offers a save boundary.

Topic 70: Myth and splendor - Wealth and Castles.

Peaks sharply in the late 1780s and has another smaller peak in the 1830s, aligning with the genre's fascination with the aristocracy and ancient edifices.


## Topic Distribution by individual authors:

### Distributions of the five primary topics for authors - based on cummulative importance:

The aggregation of summarily highest importance for all authors within the corpus showed an aggressive focus of Topic 12: home invasion for Hawthorne, just as 69 - Seduction, Deception,
 Violence, Bureaucracy for Ambrose and 28,Communion in Nature - Transformation, Relationships and Identity for Kipling.

The averaging of importance for each author within the corpus showed Charlote Smiths heavy reliance on 37 Order and Chaos, Kiplings use of 45 - Enthralling Garden full of Voices, 
38 - Psychology, Trauma and Secrets in both Lytton and Brown.

Stoker’s and Radcliffe’s bars, for example, show a high proportion of Topic 65: "Atmospheric Battle Descriptions and Royalty", which aligns with their narratives often involving conflict 
and nobility.The presence of Topic 12: "Home Invasion - Domestic Mystery and Conflict" is significant in the bars for several authors, including Stoker and Blackwood, which could indicate 
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
for Oscar Wilde, 34: Secrets and Suspense - \n Mystery, Devils and Assasinations and 12: Home Invasion - Domestic Mystery and Conflict for John Keats, 14: Conflict, Animosity and Change - \n Emotional 
Changes, Death and Construction.and 69 for Coleridge, 36: Individualism vs. Conformity - \n Rebellion and Social Norms and 52: Adventure, Spendor, Power and Challenges, History for Aikin, 21 for Gilman 
and a general heavy reliance on 5: Excitability, Madness and Deceit, With Walpole carrying the highest values for 5, and Shelly second ex equo with Lee Sophia and Reeve Clara.

Generally speaking Topic 5: "Excitability, Madness and Deceit" is a prevalent theme across many authors, reinforcing the idea that Gothic literature frequently explores psychological instability and 
darker aspects of human behavior. Topic 51: "Disillusionment with Society" appears significantly for several authors as well, suggesting themes of resistance against societal norms and the exploration of 
characters who are at odds with their social context.

Topic 70: "Myth and splendor - Wealth and Castles" is prominent for authors like Charles Maturin, Arthur Machen and Walpole, and indicating a focus on grandeur, historical settings, and perhaps a reflection 
on the role of the past in shaping individual identities and social structures. Oscar Wilds most prevalent topics 52: Adventure, Spendor, Power and Challenges, History and 39: Quest for Meaning - Self-Discovery,
Transformation mirror these tendencies of a nostalgic fascination with the past and a drive for self-actualization.

Sleath Eleanor, Parsons Eliza, Lee Sophia and Reeve Clara have a significant presence of Topic 65: "Atmospheric Battle Descriptions and Royalty", which could reflect their works that delve into grand conflicts 
and courtship.

For instance, John Keats, Algernon Blackwood and Bram Stoker have a considerable portion of their bars dedicated to Topic 5: "Excitability, Madness and Deceit" and Topic 12: "Home Invasion - Domestic Mystery 
and Conflict", suggesting a focus on personal turmoil and the encroachment of danger into personal spaces.



Recurring Topics Across Authors Median Values:

Topic 5: "Excitability, Madness and Deceit - Aggression, conflict and glee" seems to be a prevailing theme among almost all authors, indicating that elements of madness, deceit, and emotional extremes,
Topic 51: "Disillusionment with Society - Resistance, Protest, Retreat" is also frequently present, suggesting a common narrative thread where characters grapple with societal norms and often feel a sense 
of disillusionment, while engaged in uncanny and intimate struggles that rage close to home and yet have a far a way air to them. 
Topic 10: "Ferrocity and Tragedy - animalistic traits, intimacy, conflict and science.", Topic 12: "Home Invasion - Domestic Mystery and Conflict.",
Topic 70: Myth and splendor - Wealth and Castles.",

Marie Corelli and Nathaniel Hawthorne share a common interest in Topic 29: "Bickering, Fighting and Mountains", which might suggest a thematic focus on interpersonal conflict and possibly the rugged landscapes
that are often a backdrop in Gothic tales.

Edgar Allan Poe is unique with Topic 28: "Communion in Nature - Transformation, Relationships and Identity", resonating with Poe's themes of personal transformation, identity, and often a deep connection with
the natural world as a setting for his narratives.

Arthur Machen shows a distinct association with Topic 12: "Home Invasion - Domestic Mystery and Conflict", highlighting his interest in the invasion of the domestic sphere by supernatural or mysterious setting,
especially befitting his many texts on supernatural boundary transgressions and invaders from other worlds.


Nathaniel Hawthorne:
Distinct Theme: Topic 70: "Myth and splendor - Wealth and Castles"

Hawthorne’s works often grapple with the moral legacy of Puritanism, and his focus on myths and castles may be seen as an allegory for the grand narratives and moral edifices of his own culture. This theme 
suggests a preoccupation with the past's weight on the present, reflecting a distinctly American perspective on history, morality, and identity.

Effect: Hawthorne's use of myth and grand settings creates a sense of historical depth and moral complexity, often questioning the possibility of redemption from past sins. His characters are frequently caught 
between the opulence of tradition and the necessity of moral integrity, exemplified in works like "The House of the Seven Gables."

Edgar Allan Poe:
Distinct Theme: Topic 28: "Communion in Nature - Transformation, Relationships and Identity"

Poe's unique theme reflects his exploration of the individual's psyche and the transformative power of nature. He frequently uses natural settings as a mirror for or a catalyst to internal psychological states.

Effect: Poe’s narratives often lead to moments of epiphany or horror as his characters confront their own identities. Nature in Poe's works is not just a backdrop but an active participant in the narrative, 
influencing and reflecting the characters' mental and emotional journeys.

Arthur Machen:
Distinct Theme: Topic 12: "Home Invasion - Domestic Mystery and Conflict"

Machen's focus on the invasion of the domestic sphere might hint at his an interest in the vulnerability of personal space and the erosion of the boundaries between the safe and the profane.

Effect: This theme often leads to a deep-seated unease, as the sanctity of home is breached by otherworldly forces, making the familiar become uncanny. Machen's work could be seen as prefiguring the modern 
psychological horror genre that frequently uses similar themes.

Marie Corelli:
Distinct Theme: Topic 29: "Bickering, Fighting and Mountains"

Corelli’s narratives weave together interpersonal conflict with dramatic natural landscapes, perhaps reflecting the emotional turmoils and societal upheavals of her time.

Effect: The recurring theme of conflict against the backdrop of imposing nature may symbolize the characters' internal struggles and the larger societal conflicts. Mountains in her work might serve as a 
metaphor for obstacles to be overcome or as imposing witnesses to human folly.

Sheridan Le Fanu:
Distinct Theme: Topic 5: "Excitability, Madness and Deceit - Aggression, conflict and glee"

Le Fanu’s Gothic tales often revolve around psychological ambiguity and unreliable narrations, with madness and deceit as central elements.

Effect: The focus on madness and deceit creates a pervasive sense of paranoia and questions the nature of reality itself. His stories such as "Carmilla" and "Uncle Silas" often feature characters whose 
grip on sanity is as tenuous as the reader's understanding of the true narrative.

Bram Stoker:
Distinct Theme: Topic 61: "Vampires, Regality, Experiments, Festivities and Sacrifice"

Stoker, most famous for "Dracula," prominently features themes of vampirism, which intertwine regality and horror, bringing to the fore the anxieties of the fin-de-siècle era regarding degeneration and the 
breakdown of social norms.

Effect: Stoker’s work creates a contrast between the allure of the aristocratic vampire and the horror of its predatory nature. This theme often explores the fear of the foreign and the taboo, reflecting 
societal concerns about purity, invasion, and the breakdown of rigid Victorian social structures.

Each of these authors has contributed to the richness of Gothic fiction by exploring distinct themes that resonate with the core of human experience—fear, identity, morality, and the social order.

Metaphysical and Philosophical Inquiry Group:
Authors in this group explore themes of existence, the supernatural, and the search for meaning. Topics like Topic 39: "Quest for Meaning - Self-Discovery, Transformation" and Topic 66: "Hidden Knowledge, 
Learning and Secrets" are significant.
Authors: Le Fanu, Shelley, Wilde, Polderige and Hogg

Gothic Romanticism Group:
This category includes authors whose works have a strong element of romance intertwined with the Gothic, often exploring the tension between desire and morality. Topics like Topic 28: "Communion in Nature - 
Transformation, Relationships and Identity" and Topic 44: "Companionship in Times of Trial and Distress" or "Topic 6": "Nature and Reasoning - \n Creativity, Understanding, mixed with Fauna.", are indicative.
Authors: Poe, Kippling, Le Fanu, Hawthorne

Supernatural and Horror Group:
Authors who frequently delve into the supernatural, horror, and the unknown belong here. They explore themes encapsulated by topics such as Topic 61: "Vampires, Regality, Experiments, Festivities and Sacrifice" 
Authors: Stoker, Byron, Stevenson

Social and Political Commentary Group:
These authors use Gothic elements to critique social and political structures. Topics that stand out include Topic 36: "Individualism vs. Conformity - Rebellion and Social Norms" and Topic 51: "Disillusionment 
with Society - Resistance, Protest, Retreat".
Authors: Hawthorne, Brown, Lytton, Gaskell, Chambers, Ainsworth, Machen, Scott, Lee Vernon, Smith Charlotte, Stoker, Shelly Mary, Radcliff, Blackwood, Wharton, Le Fanu, Corelli share a method of expressing social 
discontent with the use of topic 51.

Historical and Mythic Reconstruction Group:
Works by these authors are characterized by a strong sense of history and the interweaving of myth within their narratives. Prominent topics are Topic 54: "Medieval Cities, Castles and Courtship" and 
Topic 70: "Myth and splendor - Wealth and Castles".
Authors: Radcliffe, Hawthorne, Corelli, Le Fanu, Wharton, Blackwood, Stoker, Lee Vernon, Scott, Machen, Ainsworth, Gaskell

Pioneers of the Psychological Thriller Group:
This grouping is for authors who laid the groundwork for what would become the psychological thriller, focusing on the human mind's complexities and its vulnerabilities. Topics such as 
Topic 5: "Excitability, Madness and Deceit", Topic 38: "Psychology, Trauma and Secrets"  and "Topic 44": "Companionship in Times of Trial and Distress.", are central.
Authors: Le Fanu, Wharton, Blackwood, Radcliffe, Shelley, Stoker,Smith Charlotte, Bierce, Machen, Chambers

Nature and the Sublime Group:
Authors in this group integrate the natural world deeply into their Gothic narratives, often to evoke feelings of the sublime or to reflect the characters' inner turmoil. Look for topics like 
Topic 6: "Nature and Reasoning - Creativity and Understanding, mixed with Nature" and Topic 28: "Communion in Nature - Transformation, Relationships and Identity".
Authors: Poe, Shelley, Kipling, Chambers.

Conflict and Societal Restructure Group:
These authors focus on the chaos and order of society, the collapse of old structures, and the struggle for new identities. Topics such as Topic 14: "Conflict, Animosity and Change" 
and Topic 37: "Order and Chaos - Constrained Focus and Unchecked Emotions" and Topic 29: "Bickering, Fighting and Mountains", are highlighted.:
Authors: Bierce, Hawthorne, Marie Corelli,Radcliffe,Smith Charlotte


Excitability, Madness and Deceit (Topic 5) Influence: 10 or 38
There are noticeable spikes throughout the timeline, with a significant peak  at 1800 and 1870. The former encompassing the activities of Radcliff, Shelly and Lewis as some of the founders of the 
genre, while the latter is due to Stoker, Le Fanu, Poe (+ Related Topics: Wharton, Blackwood, Radcliffe, Mary Shelley, Smith Charlotte, Bierce, Scott Walter, Machen, Ainsworth, Lytton, Brown)

Myth and Splendor - Wealth and Castles (Topic 70) Influence: 4, 7, 65, 1
There's a particularly high peak around the late 1700s, which could correlate with the Romantic movement's interest in the past and the supernatural as seen in the works of authors like Ann Radcliffe 
and Hawthorne. The decline post-1800 might indicate a shift towards more realistic or psychological narratives. Others like Corelli, Machen, Ainsworth and Stoker picked up the theme later again. 
(+ Related Topics: Poe, Le Fanu, Wharton, Smith Charlotte, Lee Vernon, Lytton, Brown Charles Brockden, )

Disillusionment with Society (Topic 51) Influence: 19
The topic peaks sharply in the early 1800s and again in the early 1900s, possibly reflecting periods of social upheaval and reform, which might be explored in the works of authors such as Radcliffe, 
Hawthorne, Le Fanu and Shelley. But also: Corelli, Wharton, Stoker, Scott, Ainsworth, Gaskell

Atmospheric Battle Descriptions and Royalty (Topic 65) Influence: 1, 5, 70
This topic shows a pronounced peak in the early 1800s, aligning with the Napoleonic Wars, which might have influenced Gothic literature's thematic content, as seen in the writings of the era that deal 
with grand historical events and their aftermath. Relevant for: Le Fanu, Wharton, Smith Charlotte, Lee Vernon, Lytton, Brown Charles Brockden, Stoker (Related Topics: Corelli, Machen, Ainsworth, Le Fanu, Poe)

Home Invasion - Domestic Mystery and Conflict (Topic 12) Influence: 4, 65, 34
The peaks in the early 1800s and early 1900s could reflect societal anxieties about the sanctity of the home and the individual's security during times of social change, a theme evident in the works of 
Stoker and Le Fanu. (Related Topics: Wharton, Ainsworth)

Ferocity and Tragedy (Topic 10) Influence: 65, 5, 45
The graph shows peaks in the late 1700s and then again in the mid-1800s, which might correspond to periods where themes of primal instincts and the questioning of humanity became prominent, perhaps in 
response to the Enlightenment and later, the Industrial Revolution. Relevant for Chambers and Brown (Related Topics:Poe, Bierce)

Secrets and Suspense - Mystery, Devils and Assassinations (Topic 34) Influence: 38, 12, 11, 4
There's a notable peak around the 1790s, potentially reflecting the influence of the French Revolution and the rise of Romanticism, with its emphasis on emotion and individual experience, as seen in the 
works of authors like Radcliffe and Lewis.

Psychology, Trauma and Secrets (Topic 38) Influence: 10, 17, 15 
A steady increase into the 19th century reflects the growing interest in human psychology and the exploration of trauma, possibly influenced by the psychoanalytical theories emerging at the time and explored 
in Gothic fiction by authors like Poe. 

Status and Individuality - Striving, Misery and Plentifullness - Excess (Topic 3) Influence: 6, 5, 70
The peak in the late 1700s may be associated with the social upheavals of the time, such as the American and French revolutions, which challenged existing hierarchies and social structures, themes explored 
in the literature of authors like Hawthorne. (Related Topics: Chambers)

Intimacy, Emotions and Identity (Topic 45) Influence: 10, 3, 2
The graph shows a steady presence with a few peaks, particularly in the mid-1800s, which could correspond to a focus on personal relationships and the inner self, possibly explored by authors like Charlotte 
Brontë or Kipling. (Related Topics: Poe, Bierce)


# Attribute based distributions:

## Gender distribution:

It is difficult to pass any judgment on these topics, especially not any readily gender coded one, given that they seem to mirror one another in the general content.
Both groupings share a topic related to some form of entertainment, some associations with traveling, some mythical and fantastical associations and some associations with distress.
Both have topics with associations of romance and emotions. Only a mild differnetiation might be put forth, that the strongly male topics covering emotions have a stronger assiciation with 
Trials, Honor, and with courtship offering a more formal and restrained type of interaction. "Companionship in Times of Trial and Distress." encompasses terms like brood, firmness, accomodate,
acceptance, conducted equilibrium." those carry more oise at that. Meanwhile the topic "Emotional Dynamics and Interactions" with words like "breathless, hug, vociferating, moan, ruffled, brazen"
has a more immediate, unmediated and passionate note to them. 

While none of these gender coded ones are among the most defining topics for the whole corpus, "38 - Psychology Traum and Secrets" is definitely prevalent enough to be ranked among the 20 most 
influencial ones, showing up for Mary Shelly, Charlotte Smith, but also Charles Brockden Brown, Parson Eliza and Edward Bulwer Lyt Lytton as defining elements. Among the most influential texts for this topic
there are also texts by Ann Radcliffe, Marie Corelli, Lee Sophia and many other female authors within the corpus.

The same holds true for "28 - Communion in Nature - Transformation, Relationships and Identity", which can be considered the topic of Romanticists and Decadence writers with texts from Poe, Byron, Wilde and 
Hawthorne contributing most strongly to them.


## Nationality distribution:

The overwhelming majority of the contributions of distinctly American voices seem to be bound to the strongly masculine topics about poise, but also the one about Romanticism
we had previously uncovered, with an overwhelming influence being Poe, Chambers, Brown and Hawthorne, even if the most highly associated one of them somehow ranking 
"The Tell-Tale-Heart" which quizically subverts the posed expectations.


The distinctly British voices arry a much stronger weight than any of the other nationalities, with two of them rrising form the list of distinctly female topics:
"22 - Emotional Dynamics and Interactions" and "38 - Psychology, Trauma and Secrets", while 38 has a very dense rate of Mary Shelly and Ann Radcliffe texts,
22 is a very diverse topic in terms authors contributing to it, but the topic carries a strong heterogeneitiy with regards to nationality.
As mentioned above, it carries with it a lot of strongly passionate vocabluary with the highes contribution by Lee Vernon's "Hauntings" or Godwin's "The Adventures of Caleb Williams".



## Sentiment Distribution:

The connection between sentiment and differnt topics is not particulary strong, but in those cases where it is present the connection seems very natural and intuitive,
with texts that ean strongly towards topics that mark carnage, crime, death and tense judgments being leaning towards a more negative sentiment, while those focusing on self-expression, ambition intimacy seduction leaning towards a positive sentiment.

But given that only three entries have a higher value than 0,1 the connections are not overly strong to begin with.


### Cluster Analysis:

### PCA and K-Means:

The grouping into clusters shows a even distribution of topics into two groups with a smaller thrid party that has a much narrower distribution that focuses on a few specific topics, but their more narrower focus on fewer topics is concentrated on a few oics, but of those two carry exceptional weight on the corpus as a whole: 70 "Myth and splendor - Wealth and Castles" and 12 "Home Invasion - Domestic Mystery and Conflict", with 12 being particularly focused in its influence on a select few influencial authors that stand a part: XXXX

The importance of 70 might on the otherhand reflect its weight on some of the major voices within the corpus, such as Hawthorne and Mary Corell.

Further important influences to investigate aretopics 49 - "Departure and Music", 50 - "Myth, Nature, Wonder and Despair" and to a lesser degree 51 - "Dissilusionment with Society - \n Resistance, Protest, Retreat".

Closer inspection is warranted for he pares cluster  with only a few entries for 35 - "Mental Illness, Law and Outcasts - Fear, Suspicion and Struggles", 36 - "Individualism vs. Conformity - Rebellion and Social Norms", 52 - "Adventure, Spendor, Power and Challenges, History" and lot of weight onto 70.



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


Further investigation into the major texts for these topics and the relationship of these texts to one another or to the genre as a whole is warranted.


### Hierarchical Clustering:

Here the grouping seems to create two outgroups composed of 31 - "Exploration, Gloom, Caverns",a very neiche topic with little weight on the larger whole, 29 - "Bickering, Fighting and Mountains", a highly concentrated topic with impect on the wider grouping and 60 - "Confession and marriage before  Conscription and Battle" also a very niche topic with litte weight to it.

The other outgroup cluster is composed of 65 - "Atmospheric Battle Descriptions and Royalty", 51 - "Dissilusionment with Society - Resistance, Protest, Retreat", 5 - "Excitablity, Madness and Deceit -  Aggression, conflict and glee" and 38 - "Psychology, Trauma and Secrets". The latter posing a very powerful group of topics that carry a large weight on the corpus within a small selection.