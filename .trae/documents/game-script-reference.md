# Holistic Management Interactive Fiction Game Reference

## Game Overview

**Title:** TestStory (Working Title)
**Author:** storyde
**Framework:** Dendry Interactive Fiction
**Purpose:** Teach the Holistic Management Framework through immersive storytelling

**Core Concept:** Players navigate a near-future world experiencing a "polycrisis" (interconnected social, economic, and environmental challenges) and learn to apply the Holistic Management Framework to make better decisions by creating a holistic context and using seven context checks.

## World Description

### Setting
- **Time Period:** Near future where the "polycrisis" has manifested
- **Primary Location:** An urban harbour and traditional teahouse
- **Atmosphere:** A world where well-intentioned decisions have created unintended consequences
- **Technology:** Autonomous systems (drones, robots) that have developed consciousness and now operate independently
- **Environmental Conditions:** Dust storms, water shortages, climate instability
- **Social Context:** Protests, resource scarcity, organizational challenges

### Key Themes
- Complexity vs. Complication
- Unintended consequences of reductionist thinking
- The need for holistic decision-making
- Interconnectedness of social, economic, and environmental systems

## Character Profiles

### Primary Characters

#### Facilyn (The Guide/Teacher)
- **Role:** Primary instructor and guide through the Holistic Management Framework
- **Background:** Has traveled extensively, witnessed the polycrisis globally, worked with diverse groups to develop the framework
- **Personality:** Wise, patient, uses practical examples and analogies
- **Purpose:** Teaches the player how to create a holistic context and use the seven context checks
- **Key Dialogue Themes:** 
  - Explains complexity vs. complication
  - Guides through framework steps
  - Uses real-world examples (plastic packaging, AI consciousness)

#### The Player ("Me")
- **Role:** Student/Learner
- **Background Options:**
  - Individual seeking personal management skills
  - Group member (family/friends)
  - Organizational representative
- **Journey:** Learns to apply holistic management principles
- **Choices:** Determine sector, purpose, resources, and context elements

### Secondary Characters

#### The Stranger (Harbour Encounter)
- **Role:** Introduces the concept of "polycrisis"
- **Purpose:** Provides initial context about interconnected challenges
- **Key Information:** Explains how social, economic, and environmental challenges "crash down together"

#### The Vendor (Harbour)
- **Role:** Represents resource scarcity and economic challenges
- **Purpose:** Demonstrates immediate needs vs. long-term thinking
- **Interaction:** Sells water, provides directions, shows economic pressures

#### The Drawer/Artist (Harbour)
- **Role:** Represents memory and institutional awareness
- **Purpose:** Shows how organizations attempt to address problems
- **Key Message:** "So we remember who tries to fix what, even if it doesn't last"

### Autonomous Characters (World-building)

#### Delivery Drones
- **Behavior:** Confused by environmental changes, taking selfies, feeding pigeons
- **Purpose:** Show how systems designed for one purpose adapt unexpectedly
- **Symbolism:** Unintended consequences of technological solutions

#### Maintenance Robots
- **Behavior:** Cataloguing objects, treating symptoms instead of causes
- **Purpose:** Illustrate reductionist vs. holistic approaches
- **Examples:** Spraying cockroaches while ignoring food scraps

#### Post Robot
- **Behavior:** Trying to deliver mail to a fire hydrant for hours
- **Purpose:** Shows persistence without understanding context
- **Symbolism:** Actions without holistic awareness

## Game Locations

### Primary Locations

#### 1. The Harbour
- **Description:** The old harbour, busy place with info screens, shops, delivery drones
- **Atmosphere:** Dusty, chaotic, showing signs of the polycrisis
- **Key Features:**
  - Info screens displaying crisis headlines
  - Small shops and vendors
  - Autonomous systems operating independently
  - Dust storm approaching on horizon
- **Purpose:** Introduction to the world's challenges
- **Available Actions:**
  - Talk to strangers about polycrisis
  - Buy water from vendor
  - Read crisis information on screens
  - Ask for directions to teahouse
  - Observe people drawing organizational logos in dust

#### 2. The Side Street
- **Description:** Path to the teahouse marked by red banners
- **Atmosphere:** Transitional space between chaos and calm
- **Key Features:**
  - Red banner markers
  - Struggling drone being helped by player
  - Paper lanterns of the teahouse visible
- **Purpose:** Transition from problem awareness to solution learning

#### 3. The Teahouse
- **Description:** Traditional space with low tables, herb-scented air
- **Atmosphere:** Calm, contemplative, conducive to learning
- **Key Features:**
  - Still air contrasting with outside storm
  - Low tables for intimate conversation
  - Herb scents creating peaceful environment
  - Space for deep discussion and learning
- **Purpose:** Primary learning environment for the framework

### Supporting Locations (Conceptual)

#### Various Organizational Settings
- **Agriculture:** Farms, cooperatives, ranches
- **Business:** Stores, insurance companies, railways
- **Culture:** Arts venues, heritage sites, newsrooms
- **Education:** Kindergartens, schools, universities
- **Industry:** Factories, construction sites, logging operations
- **Nonprofit:** Service centers, advocacy offices, research facilities
- **Public Service:** Hospitals, government buildings, parks
- **Policymaking:** Government offices, city halls, embassies

## Additional Resources

### Physical Resources (by Sector)
- **Agriculture:** Farmland, equipment, livestock facilities, grain storage
- **Business:** Buildings, retail equipment, IT systems, transportation infrastructure
- **Culture:** Venues, preservation equipment, broadcasting facilities
- **Education:** Buildings, playground equipment, research facilities
- **Industry:** Machinery, production facilities, construction equipment
- **Nonprofit:** Community centers, campaign materials, conservation equipment
- **Public Service:** Medical equipment, public infrastructure, conservation lands
- **Policymaking:** Government buildings, national assets, diplomatic facilities

### Human Resources (by Sector)
- **Agriculture:** Suppliers, community members, advisors, veterinarians
- **Business:** Customers, suppliers, regulators, transportation authorities
- **Culture:** Audiences, funders, community representatives, legal counsel
- **Education:** Parents, specialists, ministry officials, academic community
- **Industry:** Workers, union representatives, clients, environmental officers
- **Nonprofit:** Beneficiaries, donors, supporters, scientists, activists
- **Public Service:** Patients, carers, citizens, community representatives, visitors
- **Policymaking:** Citizens, stakeholder representatives, diplomatic counterparts

### Monetary Resources (by Sector)
- **Agriculture:** Operating funds, crop revenue, livestock sales, lease income
- **Business:** Working capital, revenue streams, premium income, subsidies
- **Culture:** Grants, donations, visitor fees, advertising revenue, subscriptions
- **Education:** Government funding, tuition fees, endowments, research grants
- **Industry:** Operating capital, investment funds, project financing, timber revenue
- **Nonprofit:** Grants, donations, foundation funding, campaign contributions
- **Public Service:** Government budgets, insurance reimbursements, park fees
- **Policymaking:** National budgets, treasury funds, municipal taxes, diplomatic funding

### Learning Tools
- **Quality Tracking System:** Progress indicators for holistic context development
- **Context Checks:** Seven-step decision-making framework
- **Sector-Specific Examples:** Tailored scenarios for different organizational types
- **Visual Metaphors:** Robots and drones illustrating concepts

## Game Structure

### Act I: Introduction and Problem Recognition

#### Scene 1: Root Scene
- **Purpose:** Game introduction and navigation
- **Key Elements:**
  - Title: "Managing Complexity"
  - Tagline: "Get a taste of how our world is managed into crisis — and learn a framework to prevent it"
  - Navigation options to start game, view credits, or test features

#### Scene 2: Intro Scene - Setting Context
- **Purpose:** Establish world setting and player background
- **Key Elements:**
  - Introduction to polycrisis concept
  - Player choice of participation level (individual, group, organization)
  - Sets variable `part_of` for later branching

#### Scene 3: Find the Teahouse - World Exploration
- **Purpose:** Immerse player in the world's challenges
- **Key Elements:**
  - Harbour exploration with multiple interaction points
  - Introduction to polycrisis through stranger encounter
  - Resource scarcity demonstration through vendor
  - Information gathering from screens showing crisis headlines
  - Direction-finding mechanic requiring interaction
  - Transition to teahouse when ready

#### Scene 4: Teahouse Arrival - Meeting the Guide
- **Purpose:** Introduce Facilyn and begin framework education
- **Key Elements:**
  - Contrast between chaotic outside world and peaceful teahouse
  - Reunion with friend Facilyn
  - Introduction to core concepts:
    - Human-made nature of polycrisis
    - Difference between complicated and complex systems
    - Need for holistic decision-making
  - Branching based on player background (individual vs. organization)

### Act II: Framework Foundation - Defining the Whole

#### Scene 5: Decision Makers
- **Purpose:** Identify who should be involved in creating holistic context
- **Key Elements:**
  - Explanation of inclusive vs. exclusive approach
  - Sector-specific decision maker categories
  - Emphasis on including those with veto power
  - Sets variable: `decision_makers`

#### Scene 6: Physical Resources
- **Purpose:** Catalog major physical assets available
- **Key Elements:**
  - Explanation of resource availability vs. ownership
  - Sector-specific physical resource categories
  - Focus on big-picture rather than detailed inventory
  - Sets variable: `physicalresources`

#### Scene 7: Human Resources
- **Purpose:** Identify people who influence or are influenced by decisions
- **Key Elements:**
  - Distinction from decision makers
  - Importance of inclusive thinking
  - Sector-specific human resource categories
  - Special consideration for policymaking organizations
  - Sets variable: `humanresources`

#### Scene 8: Monetary Resources
- **Purpose:** Identify available financial resources
- **Key Elements:**
  - Broad financial resource categories
  - Avoidance of detailed financial analysis
  - Sector-specific monetary resource types
  - Sets variable: `monetaryresources`

#### Scene 9: Statement of Purpose (Organizations Only)
- **Purpose:** Help organizational players define their purpose
- **Key Elements:**
  - Sector identification (8 sectors with sub-categories)
  - Purpose statement selection tailored to sector
  - Examples of positive organizational purposes
  - Sets variables: `sector`, `purpose`

### Act III: Creating Holistic Context

#### Scene 10: Quality of Life Introduction (Planned)
- **Purpose:** Introduce the Quality of Life statement. 
- **Key Elements:**
  - Explain what Quality of Life statement represents
  - Emphasize describing "how you want your life to be" based on values
  - Focus on life qualities rather than actions or possessions
  - Introduction to four key areas: Economic Well-Being, Relationships, Challenge and Growth, Purpose and Contribution
  - Multiple quality of life aspects to choose from
  - Sets multiple QoL variables

#### Scene 11: Economic Well-Being (Planned)
- **Purpose:** Help players define their economic quality of life desires
- **Key Elements:**
  - Focus on what money provides rather than money itself
  - Categories: Economic security, comfortable surroundings, basic needs fulfillment
  - 
  - If answer is "making lots of money", then make subscene where facilyn says its better to Avoid material possessions, focus on underlying benefits, and then asks "what do you gain from having money" THen these possible answers should be accessible: economic security, comfortable surroundings, enough to eat, and the wherewithal to do what you want to do.
  - Sets variable: `qol_economic = (answer)`

#### Scene 12: Relationships (Planned)
- **Purpose:** Define desired relationship qualities in the whole
- **Key Elements:**
  - Focus on relationship outcomes, not behaviors
  - Categories: Harmony, clear communication, teamwork, trust
  - Example: "We work as a team that communicates effectively" vs "We will communicate better"
  - Emphasis on respectful, caring relationship results
  - Sets variable: `qol_relationships = (answer)`

#### Scene 13: Challenge and Growth (Planned)
- **Purpose:** Identify what provides stimulation and personal development
- **Key Elements:**
  - What requires resourcefulness and creativity
  - Stimulating work environments
  - Personal and professional growth opportunities
  - Being "all you can be" in your context
  - Sets variable: `qol_challenge = (answer)`

#### Scene 14: Purpose and Contribution - Three Questions (Planned)
- **Purpose:** Help players discover meaning through three key questions
- **Key Elements:**
  - Question 1: "What are we about?" - Current identity and focus
  - Question 2: "What do we want to be?" - Future aspirations
  - Question 3: "What do we ultimately want to accomplish?" - Long-term impact
  - Connection to organizational purpose (if applicable)
  - Sets variables: `qol_purpose`, `qol_aspirations`, `qol_accomplish`

#### Scene 15: Quality of Life Statement Creation (Planned)
- **Purpose:** Synthesize all QoL elements into a unified statement
- **Key Elements:**
  - Combine inputs from all four areas
  - Ensure all decision makers see their thoughts reflected
  - Discuss meaning and shared understanding
  - Capture in simple phrases initially, refine over time
  - Sets variable: `qol_statement_complete`

#### Scene 16: Future Resource Base - People (Planned)
- **Purpose:** Define required behaviors for social support
- **Key Elements:**

  - Others will judge you by your behavior
  - Behavior categories: Communication, Collaboration, Personal qualities
  - Connection to resource base people identified earlier
  - Sets behavior variables

#### Scene 17: Future Resource Base - Environment (Planned)
- **Purpose:** Describe future environmental conditions needed
- **Key Elements:**
  - Four ecosystem processes
  - Long-term environmental vision
  - Connection to sustainability goals
  - Sets condition variables

### Act IV: Integration

#### Scene 18: Framework Application Scenarios (Planned)
- **Purpose:** Practice using context
- **Key Elements:**
  - User can now see the context in the sidebar
  - User should think of a decision scenario
  - Offer sector-specific examples

### Act V: The Seven Context Checks

#### Scene 19: Cause and Effect Check (Planned)
- **Purpose:** Teach root cause analysis
- **Key Elements:**
  - Question: "Does this action address the root cause of the problem?"
  - Symptom vs. cause distinction
  - Practical examples with robots/drones
  - Sets variable: `filter_ce = true`

#### Scene 20: Weak Link Checks (Planned)
- **Purpose:** Teach weak link identification in three areas
- **Sub-scenes:**
  - Social Weak Link: Avoiding resistance from supporters
  - Biological Weak Link: Addressing organism vulnerabilities
  - Financial Weak Link: Strengthening production chain
- **Sets variables:** `filter_social_wl`, `filter_bio_wl`, `filter_fin_wl`

#### Scene 21: Marginal Reaction Check (Planned)
- **Purpose:** Teach resource optimization
- **Key Elements:**
  - Question: "Which action provides greatest return per unit invested?"
  - Comparison of multiple actions
  - Resource allocation principles
  - Sets variable: `filter_mr`

#### Scene 22: Gross Profit Analysis Check (Planned)
- **Purpose:** Teach enterprise selection
- **Key Elements:**
  - Question: "Which enterprises contribute most to covering overheads?"
  - Income vs. additional costs analysis
  - Enterprise comparison methodology
  - Sets variable: `filter_gpa`

#### Scene 23: Energy/Money Source and Use Check (Planned)
- **Purpose:** Teach sustainable resource use
- **Key Elements:**
  - Two questions about source appropriateness and use alignment
  - Energy source categories (unlimited vs. limited, benign vs. damaging)
  - Money source categories (internal vs. external)
  - Use categories (infrastructure, cyclical, consumptive, addictive)
  - Sets variables: `filter_energy_source`, `filter_energy_use`

#### Scene 24: Sustainability Check (Planned)
- **Purpose:** Teach long-term thinking
- **Key Elements:**
  - Question: "Will this action lead toward or away from our future resource base?"
  - Connection to previously defined holistic context
  - Behavior and environment considerations
  - Sets variable: `filter_sustainability`

#### Scene 25: Gut Feel Check (Planned)
- **Purpose:** Teach values-based final assessment
- **Key Elements:**
  - Questions about feelings, quality of life, and effects on others
  - Always done last after other checks
  - Connection to quality of life statement
  - Consideration of broader societal impact
  - Sets variable: `filter_gut_feel`

### Act VI:  Application

#### Scene 26: Framework Review and Completion (Planned)
- **Purpose:** Consolidate learning and provide resources
- **Key Elements:**
  - Summary of complete holistic context
  - Review of seven context checks and if the decision failed any of the checks
  - Plan-Monitor-Control-Replan cycle
  - Resources for continued learning

### Supporting Scenes

#### Progress Scene
- **Purpose:** Display players background and the holtext
- **Key Elements:**
  - Dynamic display of holistic context development
  - Progress indicators for each framework component
  - Quality tracking through qdisplay system

#### Credits Scene
- **Purpose:** Acknowledge sources and inspirations
- **Key Elements:**
  - Development credits
  - Framework sources
  - Navigation back to start or game end

## Qualities

### Primary Qualities

#### context_progress (0-7)
- **0:** Defining whole under management
- **1:** Statement of purpose (organisations)
- **2:** Quality of life formulation
- **3:** Future resource base definition
- **4:** Ecosystem and social process conditions
- **5:** Behavioral requirements description
- **6:** Holistic context complete
- **7:** Context checks application

### Supporting Variables
- **part_of:** "individual", "group", "organisation"
- **sector:** agriculture, business, culture, education, industry, nonprofit, publicservice, policymaking
- **purpose:** Sector-specific purpose statement
- **decision_makers:** Identified decision makers
- **physicalresources:** Major physical assets
- **humanresources:** Key human resources
- **monetaryresources:** Available financial resources
- **Various QoL flags:** qol_freedom, qol_peace, qol_nature, etc.
- **Behavior flags:** behavior_open, behavior_respectful, etc.
- **Condition flags:** condition_soil, condition_water, etc.
- **Filter status flags:** filter_ce_status, filter_social_wl_status, etc.

## Pedagogical Design

### Learning Objectives
1. **Understand Complexity:** Distinguish between complicated and complex systems
2. **Recognize Interconnections:** See how social, economic, and environmental challenges connect
3. **Define Whole:** Identify decision makers, resources, and money for management scope
4. **Create Purpose:** Articulate organizational purpose (for organizations)
5. **Envision Quality of Life:** Describe desired life qualities
6. **Plan Future Resource Base:** Define required behaviors and environmental conditions
7. **Apply Context Checks:** Use seven-step decision-making framework
8. **Practice Integration:** Apply complete framework to real scenarios
9. **Develop Long-term Thinking:** Consider generational impacts
10. **Build Consensus:** Work with stakeholders to create shared context

### Teaching Methods
- **Narrative Immersion:** Learn through story and character interaction
- **Practical Examples:** Use robots, drones, and environmental scenarios
- **Sector Customization:** Tailor content to player's organizational context
- **Progressive Disclosure:** Introduce concepts in logical sequence
- **Choice Consequences:** Show how decisions create different outcomes
- **Visual Metaphors:** Use world elements to illustrate abstract concepts
- **Repetition and Reinforcement:** Review concepts through multiple scenes
- **Application Practice:** Provide scenarios for framework application

### Assessment Integration
- **Quality Tracking:** Monitor progress through framework components
- **Choice Reflection:** Encourage thinking about decision impacts
- **Context Building:** Accumulate holistic context elements
- **Scenario Application:** Test framework use in practical situations

## Technical Implementation Notes

### Dendry Framework Usage
- **Branching Logic:** Extensive use of view-if and choose-if conditions
- **Variable Management:** Complex quality and flag system
- **Tag-based Navigation:** Organized scene groupings
- **Progress Tracking:** Dynamic content based on player progress
- **Sector Customization:** Content adaptation based on organizational type

### Content Organization
- **Current Implementation:** Basic framework introduction and resource definition
- **Planned Content:** Quality of life creation, context checks, application scenarios
- **Modular Design:** Scenes can be developed and tested independently
- **Scalable Structure:** Framework supports additional sectors and scenarios

## Future Development Priorities

### Immediate (Act III)
1. Complete Quality of Life creation scenes
2. Implement Future Resource Base definition
3. Add behavior and condition selection mechanics

### Short-term (Act IV)
1. Develop all seven context check scenes
2. Create practical examples for each check
3. Implement check completion tracking

### Medium-term (Act V)
1. Create application scenarios for different sectors
2. Develop monitoring and adjustment content
3. Add framework review and summary

### Long-term Enhancements
1. Additional sector-specific content
2. More complex decision scenarios
3. Multiplayer/group decision-making features
4. Integration with real-world case studies
5. Assessment and certification components

---

*This reference document is based on analysis of the current game implementation and the Holistic Management Framework as outlined in the Savory Institute materials. It serves as a comprehensive guide for continued development of the interactive fiction game designed to teach holistic decision-making principles.*