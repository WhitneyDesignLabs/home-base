HOME.BASE  1.0
A WHITNEY DESIGN LABS GAME, FOR THE APPLE IIE
whitneydesignlabs.com/homebase

It is 3:47 in the morning. On the nightstand a smart clock is making
the sound a smoke detector would make if it had opinions. You live in a
smart home that will not let you leave. Outside it is 3:47 as well:
every clock in Nestwell Meadows says so, the neighbours are asleep, and
the gate will not open until sunrise. Sunrise has been quietly
cancelled.

HOME.BASE is a text adventure with pictures: fifty rooms, six disk
sides, three endings. It runs on a 64K Apple IIe.


WHAT YOU NEED

  An Apple IIe (unenhanced or enhanced), IIc, IIc Plus, IIgs or
  Platinum IIe, with 64K and an 80-column card (the plain 1K text card
  is enough), and one 5.25-inch drive. Or an emulator of one.

  A Mockingboard in slot 4 or 5 is optional. The game finds it at boot;
  without one every sound and tune plays on the speaker.

  ProDOS 2.4.1 is on the disks. Nothing has to be installed.

  An Apple ][ or ][+ boots the disk, is told politely that this is not
  its game, and stops.


THE FILES

  HOMEBASE-A.dsk ... HOMEBASE-F.dsk   the six disk sides
  README.txt                          this file
  LICENSE.txt                         what you may do with the game
  CHECKSUMS.txt                       md5 of every file here


HOW TO START

  Put Side A in drive 1 and boot (power on, or PR#6).
  In an emulator: put HOMEBASE-A.dsk in drive 1 and restart the
  machine. In AppleWin, F3 chooses the disk for drive 1.

  A title page, a short fanfare, then any key. You are in your bedroom.

  On a real machine, write the six images to floppies (ADTPro does
  this) or put them on a Floppy Emu or similar in 5.25-inch disk mode,
  and label them A to F.


CHANGING DISKS

  The game uses one drive: the one it booted from. When it wants
  another side it says so:

      INSERT SIDE B. PRESS SPACE.

  Take the disk out, put that side in the same drive, press space.
  If the wrong disk is in the drive it says

      WRONG DISK. INSERT SIDE B.

  and waits. Put the right one in and press any key. Nothing is lost.

  When a page ends TO BE CONTINUED ON SIDE C you may change the disk
  right then, or wait to be asked. Either is fine.

  You will sometimes be sent back to Side A. That is the game, not a
  fault.


PLAYING

  Type what you want to do and press RETURN. Two or three words are
  usually enough:

      LOOK              EXAMINE CLOCK       TAKE NOTE
      INVENTORY         DROP NOTE           OPEN DOOR
      NORTH (or N)      S  E  W  UP  DOWN   WAIT

  L is LOOK, X is EXAMINE, I is INVENTORY, Z is WAIT. IT means the
  last thing you named. HELP is there if you want it.

  [MORE] at the corner of the text means there is another page:
  press any key.

  Any key ends a tune.


SAVING

  SAVE      writes your game to Side A (one saved game). If another
            side is in the drive the game asks for Side A, saves, and
            asks for your side back.
  RESTORE   reads it back.
  RESTART   begins the night again.
  QUIT      hands the machine back to ProDOS.

  Side A must not be write-protected, or SAVE cannot write. In an
  emulator, keep the Side A image file writable. The other five sides
  can be protected.

  A saved game belongs to this version of the disks.


IF SOMETHING GOES WRONG

  If the game stops, says something that cannot be right, or leaves
  you somewhere with no way on, please write down the last few things
  you typed and which side was in the drive, and open an issue at
  github.com/WhitneyDesignLabs/home-base.

  A hint sheet follows at whitneydesignlabs.com/homebase.

  CHECKSUMS.txt lets you check that a disk image arrived whole.


A WHITNEY DESIGN LABS GAME
whitneydesignlabs.com/homebase
