# SQA Take Home Challenge

# Nama: Hakim Achmad Anaffi
# Posisi: Quality Assurance Intern

## Task Create top 10 most important use cases ordered by priority with the Gherkin syntax in Whatsapp Dekstop

1. Scenario: User can login to the whatsapp desktop application
    Given I'm on the setup whatsapp page on whatsapp dekstop
    When I open the WhatsApp application on my cell phone
    And I click vertical dot icon and choose linked device
    And I click button linked device
    And I directed the scan code on the cellphone to the qr code on the WhatsApp desktop
    Then I'm on the dashboard chat

2. Scenario: User can send new chat
    Given I'm on the dashboard chat whatsapp
    When I click new chat
    And I select the contact of the user I want to message
    And I types a message in the message box
    And I click "send" button
    Then message sent successfully

3. Scenario: User can receive a message from a contact
    Given I'm on the dashboard chat whatsapp
    And I has a contact who has sent a message
    When I receives the message
    Then the message should be displayed correctly in the chat window

4. Scenario: User can make a voice call with person
    Given I'm on the dashboard chat whatsapp
    When I open the personal chat with the contact i like to call
    And I click the "voice call" icon
    Then I can talk with the person

5. Scenario: User can make a video call with person
    Given I'm on the dashboard chat whatsapp
    When I open the personal chat with the contact i like to call
    And I click the "video call" icon
    Then I can speak by looking at the face of the person being called

6. Scenario: User can delete message chat personal
    Given I'm on the dashboard chat whatsapp
    And I select one personal chat
    When I select one message in chat
    And I right click on the mouse
    And I choose icon "Trash"
    Then the message delete successfully

7. Scenario: User can pin chatting to top chat
    Given I'm on the dashboard chat whatsapp
    And I select one personal chat or group chat
    When I right click on the mouse
    And I choose  "Pin to top"
    Then the personal chat or group chat successfully to the top chat

8. Scenario: User can archive chatting 
    Given I'm on the dashboard chat whatsapp
    And I select one personal chat or group chat
    When I right click on the mouse
    And I choose  "Archive"
    Then the personal chat or group chat successfully moved to page chat archived

9. Scenario: User can search for a chat
    Given I'm on the dashboard chat whatsapp
    When I typing a search query in the search bar
    Then the relevant chats should displayed

10. Scenario: User can see contact status
    Given I'm on the dashboard chat whatsapp
    When I click status in navbar
    And I choose one of contact status
    Then I see contact status displayed




