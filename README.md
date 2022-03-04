# CNC_BANJO
This is a full sized 5 string Open Back Banjo I decided to make.<br>
It uses nylong strings, planetary geared tuners, a calfskin head and is Texas themed.<br>
The rim and neck are both made from Poplar, while the fretboard is made from Oak.

 <img src="https://github.com/caleb221/CNC_BANJO/blob/main/BANJO_IMG/IMG_20220226_140109.jpg" width=350 height=450></img>
 <img src="https://github.com/caleb221/CNC_BANJO/blob/main/BANJO_IMG/Screenshot%20from%202022-02-28%2000-18-32.png" width=300 height=350></img>
 <img src="https://github.com/caleb221/CNC_BANJO/blob/main/BANJO_IMG/IMG_20220226_140128.jpg" width=300 height=350></img>

# Model
  The banjo1.fcstd File is the CAD File for the whole banjo.<br>
  
  Fret lengths were found using the <a href="https://www.ekips.org/tools/guitar/fretfind2d/">FretFind2D Tool</a>. 
 
  A scale length of 26.375'' or 669.925mm was used.
  
  This is a standard full sized 5 String Open Back Banjo.
  
  <img src="https://github.com/caleb221/CNC_BANJO/blob/main/BANJO_IMG/Screenshot%20from%202022-02-28%2000-18-53.png" width=500 height=300></img>
  
# BUILD

  <b>RIM Ring:</b><br>
   To prepare the wood from a stick to a ring (without a steam bender or lathe)
   first cut out 8 segments of your wood stock according to<br> <a href="https://github.com/caleb221/CNC_BANJO/blob/main/NON_CNC_PLANS/BluestemBanjoRimSegmentGuide.pdf"> Blue Stem Rim Segment Guide (copy)</a>.
   I cut 36 segments of the 8 segment 11'' rim, which totaled 4 rings and a depth of about 3'' for the rim.
    
   Glue the segments together using either a jig (probably better) or a band clamp which is what I used.
   
   After the glue dries and all 4 segments are prepared, use the CNC to cut out the rings.
   
   Once the rings are cut, use the dowel holes to line up the rings and glue all 4 segments together.
   
   Once you have what should look like a rough rim, use the CNC as an upside down router table to smooth things out on both the inner and outer diameters.
   I used a flush trim bit to do this.
   
   Once it is flush, I cut a small lip around the outer diameter. 
   
   Once this process was finished, I measured out the angles needed for the hardware.
   
   This can be found as the hardware_angles array in teh freecad file
   
   I used the drill press to make these 8 holes. Along with 2 7/16'' holes on each end for the 1/4'' threaded dowel rod, tailpiece and neck attachment.
   
   <b>I had pictures of this process, but halfway through my phone decided to die, losing those pictures forever</b>
    
   <img src="https://github.com/caleb221/CNC_BANJO/blob/main/BANJO_IMG/IMG_20220122_133209.jpg" width=250 height=300></img>
   <img src="https://github.com/caleb221/CNC_BANJO/blob/main/BANJO_IMG/IMG_20220122_133220.jpg" width=250 height=300></img> 
   <img src="https://github.com/caleb221/CNC_BANJO/blob/main/BANJO_IMG/IMG_20220226_140308.jpg" width=250 height=300></img> 
    Note: The model is a bit oversized, which allows for discrepencies that arise when the rings are glued together and so that the 11'' inner diameter can be reached using the flush trim bit.
    Most of the wood preparation measurements can be found in the NON_CNC folder.
    There are also bits of information on building jigs and how to make one without a CNC.
    
  <b>RIM Hardware:</b><br>
    <br> 
    <b>Tension Hoop:</b>
      
    Get the 3 foot Steel flat bar and bend it into a ring.
    
    Use the rim to measure the exact size of the ring, and mark it. It should be oversized by a few inches.
    
    place the bent steel into a vise where it can be brazed together.
    
    The inner part of the steel bar should meet the measured mark, with the excess on the outer part.
    
    Heat the steel ring until it is red hot and braze the steel with flux and a bronze rod. 
    
    Use an Angle grinder to remove the excess flat bar, and deburr across the top.
    
  <br>
    
  <b>J hooks and Brackets:</b>
  
  <img src="https://github.com/caleb221/CNC_BANJO/blob/main/BANJO_IMG/IMG_20220122_161900.jpg" width=250 height=300></img> 
   
   Measure the approximate depth of your rim and use it for the length . 
    
   Grab the 1/4'' steel rod and put it into a vise. 
    
   using as little rod as possible create a 90 degree bend, then hammer that bend until you can see a clear hook.
    
   Cut of the excess in the hook using an angle grinder, and cut it to length (should be approximately 3/4 your rim depth).
    
   Thread at least 1/2 the length of the J hook using 1/4'' round die and cleaning with a 1/4'' hex die..
    
   Repeat until you have 8 hooks
    
     
   Use one 1/2'' coupling nut, a 1/2'' bolt and appropriate washer and thread it into place in the rim blank.
   
   Once it is in, get your steel hoop and place it where it fits snugly onto the rim.
   
   Grab a J-hook and measure the approximate location in which it will hold the hoop and sit in the coupling nut.
   
   The coupling nut should be much longer than desired.
   
   Use the mark from the J-hook to determine how much excess there is in the coupling nut.
   
   Cut out the marked hole through the coupling nut with the drill press.
   
   Use the angle grinder to cut off the excess markings on the coupling nut.
   
   repeat until you have 8 brackets.
   
   Determine if your bolts fit snugly without hitting the J-hooks, mine where a bit too long.
   
   If needed, cut down the 8 bolts to a length where they will tighten down fully without touching the J-hooks.
   
   <img src="https://github.com/caleb221/CNC_BANJO/blob/main/BANJO_IMG/IMG_20220122_143038.jpg" width=250 height=300></img> 
   <img src="https://github.com/caleb221/CNC_BANJO/blob/main/BANJO_IMG/IMG_20220226_140252.jpg" width=250 height=300></img>  
  
  <b>RIM Finishing steps:</b><br>
  
  At this point, apply any wood finish desired to the rim and let it dry. I used Boiled Linseed Oil and some minwax golden Oak.
  
  Once dry (a few days usually), test how the hardware fits together, make sure all hooks grab onto the tension ring.
  
  Also make sure the tension ring holds down the flesh hoop tightly.
  
  Disassemble and prepare the parts for the last time.
  
  Soak a calfskin (at least 13'' in diameter) in warm water for at least 30 minutes.
  
  Wrap the skin in the flesh hoop and get it in place on the rim.
  
  Put the tension hoop in place along with the J-Hooks.
  
  <img src="https://github.com/caleb221/CNC_BANJO/blob/main/BANJO_IMG/IMG_20220126_202018.jpg" width=250 height=300></img>
  <img src="https://github.com/caleb221/CNC_BANJO/blob/main/BANJO_IMG/IMG_20220126_202050.jpg" width=250 height=300></img>
  
  Tighten the J-Hooks <b>SLOWLY</b>. 
  
  Cut off the excess skin using a box cutter or any knife.
  
  <img src="https://github.com/caleb221/CNC_BANJO/blob/main/BANJO_IMG/IMG_20220127_214726.jpg" width=250 height=300></img>
  
  The skin will dry out over the next day, tighten as it will allow.
  
  <b>NECK:</b><br>
  
  Glue up the appropriate boards. I used Poplar but any hardwood will do great!
  
  Cut out the neck blank using the CNC. This will require you to flip the workpiece.
  
  The top side should be cut first as it contains the "truss" rod and that must be centered within the neck.
  
  Cut the backside. Round out the edges with a 3/4'' roundover bit.
  
  Cut out the heel blank, glue it to the neck blank using dowels to align.
  
  Glue the 3/4'' steel square bar into the neck using silicon or glue of your choice.
  
  <img src="https://github.com/caleb221/CNC_BANJO/blob/main/BANJO_IMG/IMG_20220216_194526.jpg" width=250 height=300></img>
  
  Cut out the appropriate headstock holes.
  
  Cut out the 5th string peg.
  
  Drill 2 holes at a 5 degree angle for the hangar bolt attachment to the rim.
  
  <b>Finger Board:</b><br>
  
  Prepare any 1/4'' hardwood slat onto the CNC.
  
  Cut out the artwork and contour, then backfill the artwork with epoxy resin.
  
  <img src="https://github.com/caleb221/CNC_BANJO/blob/main/BANJO_IMG/IMG_20220213_120630.jpg" width=250 height=300></img>
  <img src="https://github.com/caleb221/CNC_BANJO/blob/main/BANJO_IMG/IMG_20220214_215156.jpg" width=250 height=300></img>
  
  Fret the neck or fill in the fret slots with epoxy for a "fretless" banjo.
  
  level, sand, and crown the frets if thats the way you went. 
  
  I had enough fret wire for 12 frets, and the rest are epoxied in. A half and half compromise
  
  Glue onto the neck.
  
  <b>MISC:</b><br>
   Flesh Hoop: I used a 1/8'' Brass rod threaded and held together with a coupling nut.
   
   TailPiece: I used extra wood from the fretboard and a copper wire tied onto a 1/4'' bolt sticking out the back. 
   
   Bridge: While I did design this, I used a bridge I had obtained earlier from a banjo I built in High School.
   
# Tools
    Open Builds LEAD1010 CNC (or anything 
    Drill Press Vise
    Drill Press (the cheaper harbor freight one did this job just fine for me)
    Angle Grinder
    Power Drill
    MAP/Butane Blow torch
    Taps / Dies (SAE 1/4'' and 1/8'')
    Pull Saw
    Draw knife / spokeshave 
    Wood/Metal Rasp
    Metal Files
    Miter Box with 22.5 Degree slot
    Clamps
    Safety stuff
# BOM
    Poplar wood 
    Oak wood 
    Calfskin 16'' diamter (thin, but a thick one would work just as well)
    1/4'' steel round stock ( ~5 Feet)
    1/4'' steel square stock (~3 feet)
    1/8'' Brass rod 
    1'' coupling nuts
    1'' bolt
    18 guage steel flat bar
    1/4'' hanger bolt
    1/4'' coupling nut
    1/4'' threaded rod
    1/4'' nut
    1/4'' bolt
    1/8'' coupling nut
    Fret wire
    Imitation bone Nut blank
    Banjo Planetary tuning pegs (with 5th string peg)
    bridge (if not making the one designed)

# Consumables:
    Epoxy Resin
    Brazing Rods
    Super Glue
    Epoxy Resin
    Mica Powder
    Boiled Linseed Oil/Japan Dryer
    Sand Paper

<img src="https://github.com/caleb221/CNC_BANJO/blob/main/BANJO_IMG/IMG_20220226_140142.jpg" width=300 height=350></img>
<img src="https://github.com/caleb221/CNC_BANJO/blob/main/BANJO_IMG/IMG_20220226_140230.jpg" width=300 height=350></img>
<img src="https://github.com/caleb221/CNC_BANJO/blob/main/BANJO_IMG/IMG_20220226_140205.jpg" width=300 height=350></img>
