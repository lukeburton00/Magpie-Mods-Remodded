////A rework of the textures unlimited default stock mod, original can be found here; https://spacedock.info/mod/1841/Textures%20Unlimited%20Default%20Stock%20Config%20-%20Unofficial

////Changes:
///Edited the original stock cfg to uncover the windows, unmetalled some parts, added updated models, added new part variants from squad updates.
//Added BG compatability
//Split configs for different shades 

//// Delete unused configs to prevent logspam 

/// Want to unshine a part?
// Open the corresponding cfg look for the asset path for the part then either delete the line or put // infront of the model eg.  //model = Squad/science/partname

//// Whoah man too shiny
// Lower the smoothness value in the cfg
// or delete color value if it has one

///// Parts too dark 
/// Lower the metal value in the cfg 
// or add a color property greater than 1


//Got a cfg?
//Post it on the forum page or send a message to u/ilikeduck3 and I'll be happy to add it 

///Contributors
//Forum users; hendrack, Challyss, Mabdhi36


///// Want to write a cfg? 
// Copy a cfg then delete the models, insert paths to the models or add them to the misc cfg
// Big mods- use the ksplog
// Small mods - Model asset paths can sometimes be found easily in part cfgs or written manually linking to the mu file in the part folder


///// How to use the log:
// Boot game until it runs mm patches
// open log find Load(Model): and mod your trying to config
// copy into notepad+ delete error messages
// hold alt to highlight log info replace with model = 
// copy into a blank cfg
// boot game hunt for problems 


//////Special thanks to Shadowmage for making it possible with the TexturesUnlimited mod; https://forum.kerbalspaceprogram.com/index.php?/topic/167450-19x-textures-unlimited-pbr-shader-texture-set-and-model-loading-api/&tab=comments#comment-3216889
///And for making sstu labs, the shiny engines inspired the mod;  https://forum.kerbalspaceprogram.com/index.php?/topic/117090-wip18x-sstulabs-low-part-count-solutions-orbiters-landers-lifters-dev-thread-11-18-18/&tab=comments#comment-2090798

//// If you play stock I reccomend Manwith Noname's Recolour depot for exterioirs found; https://forum.kerbalspaceprogram.com/index.php?/topic/174188-18x-textures-unlimited-recolour-depot/ 


////Licensing 
//Wasnt sure which to put so I used the same as TU as it uses the TU shaders 