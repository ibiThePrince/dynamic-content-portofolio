# Statement of Requirements

## Stakeholders :
* Developers
* End Users (Lambda Users)

## Requirements :
* Developers :
    * Create page and section templates.
    * Ability to embed static content within page templates.
    * Ability to embed dynamic content within page templates.
        
* End Users :
    * Customization of page and section templates without touching the code.
        * Edit pages and sections contents instead.
        * Some contents are mandatory. And for the optional ones, visibility would be automacally apply 
        * Choose which pages and sections to use.
        * Customize style for pages and sections (colors, fonts).
        * Management multimedia contents such as text, images, icons, audio files, etc.

## Requirements description :
* Developers :

    * Creation of page and section templates : Developers will be responsible for creating page and section templates containing static and dynamic contents. These templates will be stored on the server's file system and their content in the database..
    * structure : Page templates will have basic content, such as a basic layout structure, reserved areas for title, main content, menus, etc. This content will serve as a starting point for end users.
    * Default content of section templates : Similarly, section templates will have default content that can be modified by end users.
    * Some contents are mandatory. And for the optional ones, visibility would be automacally apply 

* End Users :
        
    * No code / Low code : End users will be able to customize page and section templates using a user-friendly interface without requiring programming skills.
    * Select templates to use : They will be able to choose from a list of available templates for each page and section.
    * Style settings : End users will be able to select colors, fonts, and other style characteristics to apply to their pages and sections.
    * Content editing : They will be able to modify the content for pages and sections based on predefined data sets. Mandatory data will need to be provided for each section, while optional data will be displayed if available.
    * Manage multimedia content : End users will be able to add, modify, and delete multimedia elements such as text, images, icons, and audio files in their pages and sections.
        
* Assumptions :
    * There will be a user-friendly interface for end users.
    * Page and section templates will be stored on the server's file system and their content in the database.
    * The system will support customization of page and section templates based on the preferences of end users.
# Requirements Specification

## 1. User Interface:
- The system must provide a user-friendly interface accessible via a web browser.
- The interface should feature functionalities such as template selection, content editing, and visual style definition.
- The interface should be compatible with various web browsers and devices.

## 2. Template Customization:
- End users should be able to select page and section templates from a pre-established list.
- They should be able to modify template content using built-in forms or text editors.
- Users should be able to define style characteristics such as colors and fonts for each template.

## 3. Data Management:
- The system must store page and section templates, along with associated data, in a database.
- It should allow users to edit existing data and add new data via forms or dedicated interfaces.

## 4. Template Flexibility:
- Page and section templates should be designed modularly to allow easy customization by end users.
- Developers should be able to create new templates and integrate them into the system without disrupting existing functionalities.

## 5. Multimedia Content Management:
- The system must support the addition and modification of various types of multimedia content, including text, images, icons, and audio files.
- It should provide simple editing tools to manipulate this multimedia content.

## 6. Data Display Control:
- The system must manage data display based on availability, hiding containers for optional data if they are empty.
- It should allow users to define custom display rules to adapt content based on their specific needs.

# Additional Specifications

## Project forms
*For feasibility reasons, the project can take two functional forms:*
            
### Basic: branch prefixed ('basic')
functional but still require some technical skills by final users.
1. **Developers (Contributing):**
               - Create templates and push them directly to the GitHub project. 
               - A template should comprise interfaces, style and content tables, and customization forms.
               
2. **Users:**
               - Can clone the project and reuse these templates.
               - They can select pages and sections, customize style and content either directly in the DBMS or via provided forms by the developer.
            
### Complete: branch prefix ('complete')
The project's ideal form to be deployed once ready, where:
1. **Developpers:**
               - Have interfaces to post their templates (interfaces + dataset).
               - Ability to create a customization form, specifying which data from their templates each field corresponds to.
               
2. **End Users:**
               - Can choose page and section templates to create their portfolio.
               - They can export the corresponding project containing their portfolio, customization interfaces, and the associated database.
            
This additional specifications
                * outlines the two functional forms of the project, providing clarity on how developers and end users will interact with the system in each scenario.
                * Explains the branching strategy for managing different functional forms of the project.
            
