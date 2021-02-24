


           ÚÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ¿
           ³  ÕÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ¸   ³
           ³  ³  SOUND BLASTER 16 and Compatible sound cards ³   ³
           ³  ÔÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ¾   ³
           ÀÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÙ





ÄÄÄÄÂÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÂÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
    ÃÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´
    ³                  ³Û
    ³ PROGRAM LOCKS UP ³Û
    ³                  ³Û
    ÀÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÙÛ
      ßßßßßßßßßßßßßßßßßßß

If you are using a Sound Blaster 16 or compatible sound card and your
computer locks up after only a few minutes of game play, you may have
incorrect settings in the SETUP program.

If your computer does lock up, we suggest that you try the following
steps BEFORE you call Broderbund's Technical Support.  If you call
Technical Support, you will be asked to try these steps before they
can further help you.


   1) Begin at the C:> prompt.  If you are running Windows, then EXIT
      from Windows.  Do not just go into a DOS shell by clicking on
      the DOS icon, but exit Windows completely by selecting EXIT
      WINDOWS from the FILE menu in PROGRAM MANAGER.


   2) Obtain the settings for your Sound Blaster 16 card by doing
      the following:

      ù Type 'SET' and press <ENTER>

      ù Look for a line that looks like this:
        BLASTER=A220 I5 D1

      ù The A??? is the Port Address. In the example
        above, the Address is 220 Hex.

      ù The I? is the IRQ, or Interrupt, Number.  In
        the example above, the IRQ is 5.

      ù The D? is the DMA Channel.  In the example
        above, the DMA Channel is 1.

      ù All other parameters on that line can be
        ignored.

        You will need to write down the numbers for
        Port, IRQ and DMA.

        If you don't have a BLASTER line, we suggest
        that you recheck the installation of your
        sound card, or  call your sound card
        manufacturer's Technical Support department
        for appropriate assistance.


   3) Rerun the SETUP program for Carmen.

      ù Change to the Carmen directory by typing:
        CD\USAD (or CD\ and the directory name you 
        installed the game to) and press <ENTER>.

      ù Type SETUP and press <ENTER>.


   4) Use the arrow keys to select SOUND DEVICE and press <ENTER>

      ù Use the UP and DOWN arrows on your keyboard 
        to select SOUND BLASTER 16 and press <ENTER>.

      ù At the CURRENT AUDIO PARAMETER screen, check
        to see if your settings are the same as
        those you wrote down in step 2.

      ù If the settings are correct, press enter and
        go to step 5.

      ù If the settings do not match, press M to
        modify your settings.

      ù At the SELECT I/O PORT ADDRESS screen,
        select the Port Address you wrote down in
        step 2 and press <ENTER>.

      ù At  the  SELECT IRQ screen, select the IRQ
        Number you wrote down in step 2 and press
        <ENTER>.

      ù At the SELECT DMA CHANNEL screen, select the
        DMA Channel you wrote down in step 2 and
        press <ENTER>.


   5) Use the arrow keys to select MUSIC SYNTHESIZER and press
      <ENTER>.

      ù Use the arrows to select SOUND BLASTER 16
        and press <ENTER>.


   6) Use the arrows to select SAVE THE CONFIGURATION AND EXIT
      and press <ENTER>.

      ù Type Y to exit to DOS.


   7) Type CARMEN to run the game.




ÄÄÄÄÂÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÂÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
    ÃÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´
    ³                       ³Û
    ³ PROGRAM DOES NOT MUTE ³Û
    ³                       ³Û
    ÀÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÙÛ
      ßßßßßßßßßßßßßßßßßßßßßßßß

Currently our SOUND BLASTER 16 driver does not properly MUTE all
sounds.  For example, when pressing the MUTE button on the
Videophone, the music will shut off, but other sounds may
not.  If you would like to disable all program sounds, you have
three options:

   1) Lower the volume on your speakers to where no
      sounds can be heard.

   2) Run the Carmen SETUP program and select NO DEVICE
      for the SOUND and SYNTHESIZER options.

   3) Or, consult your sound card manual for the
      availability of software volume control.

