CHECK THE LOGIN 
usage of logical operators

  Write the code which asks for a login with prompt.

If the visitor enters "Admin", then prompt for a password, if the input is an empty line or Esc – show “Canceled”, if it’s another string – then show “I don’t know you”.

The password is checked as follows:

If it equals “TheMaster”, then show “Welcome!”,
Another string – show “Wrong password”,
For an empty string or cancelled input, show “Canceled”
The schema:Write the code which asks for a login with prompt.

If the visitor enters "Admin", then prompt for a password, if the input is an empty line or Esc – show “Canceled”, if it’s another string – then show “I don’t know you”.

The password is checked as follows:

If it equals “TheMaster”, then show “Welcome!”,
Another string – show “Wrong password”,
For an empty string or cancelled input, show “Canceled”
The schema:
                                    
                            BEGIN
                              |
                              |
                   ----- WHO IS THERE ----
                   |          |          |
                   |        OTHER        |
                  CANCEL      |       ADMIN
                    |         |          |
             CANCELLED     I DON'T KNOW  |
                                         |
                                  ----PASSWORD -----
                                  |       |         |
                                  |       |         |
                               CANCEL   OTHER    THE MASTER
                                |         |         |
                                |         |         |
                          CANCELLED    WRONG      WELCOME!
                                      PASSWORD