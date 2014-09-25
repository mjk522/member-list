1. Introduction
  1. Purpose of the project
    * Construct and maintain a membership list of names for Rivi&egrave;re Casino.  This electronic list should replace the existing physical system.
  2. Scope of the project
    * This project will consist of creating a membership list with maximum size 10^6 names.  This project will be completed by December 20th, 2014.  Modules of the project will consist of adding a member to the list, removing a member, editing member information, and searching the list of members.
  3. Objectives and success criteria of the project
    * This project has four primary objectives.
        1. Adding a member: Success Criteria: Completion of module that will add a member to a list.
        2. Removing a member: Success Criteria: Completion of module that will remove a member from a list.
        3. Editing a member: Success Criteria: Completion of a module that will edit member information.
        4. Searching for a member: Success Criteria: Completion of a module that will search the list for a member.
  4. Definitions, acronyms, and abbreviations
        * RC - Rivi&egrave;re Casino
        * GUI - Graphical User Interface
        * ID - Identification
  5. Overview
     * The current system is a physical member list.  This project will create an electronic member list that will replace the current system.  Being a member on this list means having access to the exclusive floor area.  Included on this exclusive floor area are higher stake tables and 2x multipler points on all games which goes towards rewards such as complimentary overnight stays or meals.  Administrative tasks and member data retention is top priority for RC.

2. Current system
  * A RC customer requests to become an exclusive member.  If the RC customer is in good standing with RC and pays a one-time membership fee, the customer may become an Exclusive member.  The RC concierge maintains a member list in a ledger which is kept near the entrance to the exclusive casino floor area.

3. Proposed system
  * Proposed system will be an electronic member list.  
  1. Overview
    * Through a GUI, this member list can be maintained by the RC concierge.  
  2. Functional requirements ("shall lists")
    1. System shall be able to dynamically add members to an existing list.  GUI shall be made for this process.
    2. System shall be able to dynamically remove members from an existing list.  GUI shall be made for this process.
    3. System shall be able to dynamically edit member information of an existing member from the list.  GUI shall be made for this process.
    4. System shall be able to search an existing list to determine if a member exists.  Searchable fields include first name, last name, and member ID.  If multiple hits, the system shall return all results with a GUI select option for the user to pick the correct results.
    5. System shall be handle all errors to prevent crashing of the program.  GUI shall show the error and direct the user to correct the error.
    6. Minimum length of a member name shall be 0 characters.
    7. Maximum length of a member name shall be 100 characters.
    8. Maximum length of the member list shall be 10^6 entries in length.
    9. Membership data history shall be kept for 100 years.  After 100 years, member data shall be destroyed.
    10. Membership data shall be backed up so no member data loss happens in case of database crashes.

  3. Nonfunctional requirements
    1. Usability
      * System will be used by a select number of people. So a small learning curve is ok as long as there is a succinct documentation to accompany the product.
    2. Reliability
      * Each command should work every time or report easy to decipher errors that allow the user to change the input where necessary.
    3. Performance
      * Results should be returned or tasks accomplished within 0.5 seconds.
    4. Supportability
      * Included in the cost for this product is a 1 year support contract.  Extensions for the support contract are available.
    5. Implementation
      * Should be implemented in a POSIX compatible environment with a stable version of PHP.
    6. Interface
      * Web interface for simplicity of use and installation.

  4. Use case models
    1. 
