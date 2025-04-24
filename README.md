# Templates for Obsidian and Supernote
 
This is a collection of templates that I use in my note-taking app Obsidian (https://obsidian.md) and on my E-Ink tablet Supernote (https://www.supernote.com).

I could use Obsidian on a Supernote device, but I have decided against it. Instead, I use a plugin in Obsidian to copy my Supernote notes to my Obsidian vault when it makes sense for me. On the other hand, I can import an Obsidian note as a PDF file to read it in Supernote or use it as a template. 

I create my Supernote templates mostly with PowerPoint and import them as PDF files. You can also use PNG images as templates, but they are rather static and only suitable for one-sided templates. In order to make my templates in Supernote more interactive, I decided to use PDF because I can link to other pages within the template. 

All the icons in my templates are from https://lucide.dev/icons/. 
I prefer the scribble style in my Supernote. That's why I redesigned the Lucide icons to match this style. For the fonts, I use Excalifont as my preferred style.
## Obsidian Templates

I use Obsidian as my second brain for note taking. To keep certain types of notes organized, I use templates. I mostly use the [Templater](https://github.com/SilentVoid13/Templater) and [Dataview](https://github.com/blacksmithgu/obsidian-dataview) plugins to code and link the notes in the vault.

The **Templater** plugin is required and the **Dataview** plugin is strongly recommended, otherwise the templates cannot be executed or, in the case of Dataview, the notes created cannot interact with each other.

It is not necessary to use all templates, but they can benefit from each other. For example, Meeting, Jour Fixe and Trip Planner can use the notes from the contact template. On the other hand, the contact notes provide you with a list of other notes to which the contact name is linked.
### Contact
I simply use this template for all my contacts and it works like an address book. Only a few pieces of information are requested during execution, e.g.
- Name (first and last name)
- Telephone number
- Company
- Job title
- Email address
- Relationship (to other contacts, e.g. reporting line, etc.)
After creation, the file is moved to the **Contacts** folder. If I also want to add the postal address, I can do this directly in the created note. 
Don't be surprised that two colons are used in the postal address. It is not a typing error, but is interpreted by the Dataview plugin as so-called [Inline Fields](https://blacksmithgu.github.io/obsidian-dataview/annotation/add-metadata/).
### Cover Pager - Cover Page TLP

The cover page template is rather optional if a cover page with company logo is required for the export of a note to make it look more official.

This template is designed with information security in mind, where I can select a file classification to mark it.

The default **Cover Page** template sets one of the following file classifications on the cover page:  
- Public 
- Internal 
- Confidential 
- Strictly confidential 

Optional, the Traffic Light Protocol ([TLP](https://www.first.org/tlp/)) classification template **Cover page TLP** sets one of the TLP labels on the cover page and the corresponding disclosure agreement text for:
- TLP:CLEAR
- TLP:GREEEN
- TLP:AMBER
- TLP:AMER+STRICT
- TLP:RED

### Jour Fixe

### Meeting

### Trip Planner

### Workshop
## Supernote Templates



## Supernote Stickers
With the March 2025 update, the Supernote devices Manta and Nomad have received the sticker feature. Not only can you use the built-in stickers in your notes, but you can also create your own sticker collections. I have also created a few collections to help me out.

### BPMN
I need Business Process Model and Notation ([BPMN](https://www.omg.org/spec/BPMN/2.0.2/PDF)) from time to time for work, and sometimes I use it to describe the workflow of my "applications" that I have created with Obsidian (e.g. https://github.com/malleVF/Threat-Research-with-Obsidian-for-SOC-Analysts). My collection contains only a small selection that I use most often for my work.

### Dashboard Design
I have created 3 collections for sketching dashboards.
Tiles in various sizes based on the 5 mm grid template from Supernote:
- **Rep-Tile Landscape**
- **Rep-Tile Portrait**
The third collection contains the diagrams. Their size can be adjusted to fit the tiles:
- **Rep-Charts**

### STIX Icons (EclecticIQ)
STIX-Icons is a collection of colourful and clean icons for use in software, training and marketing material to visualize cyber threats according to the STIX language for intelligence exchange. (credits: [EclecticIQ](https://blog.eclecticiq.com/our-journey-to-support-stix-2.1) and on [Github](https://github.com/eclecticiq/stix-icons))

### Template Icons
**Template Icons** is the collection of icons I use in PowerPoint to create interactive PDF templates. It's basically a copy of my scribbled icons from Licude. The collection helps me get my ideas down on paper before I start designing on my PC. 
You can also use it to create the templates directly in Supernote and export them as PNG images to use as templates. The process of template development via PowerPoint is not necessarily required. Fore more details: [Supernote Support Page: How to Create a Custom Note Template Using Images?](https://support.supernote.com/en_US/faq/how-to-create-a-custom-note-template)
