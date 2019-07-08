# Transparency

Ntuples location:

     /eos/cms/store/group/dpg_ecal/comm_ecal/pedestals_gainratio/


     /eos/cms/store/group/dpg_ecal/comm_ecal/pedestals_gainratio/BlueLaser_2012-2016pp_legacy.root
     /eos/cms/store/group/dpg_ecal/comm_ecal/pedestals_gainratio/BlueLaser_2017_rereco_v2_newformat.root
     /eos/cms/store/group/dpg_ecal/comm_ecal/pedestals_gainratio/BlueLaser_2018_v1_rereco.root



Questions:

    Should effective corrections be included? Should it learn about drifts?
    If yes, intergrate with IC tag

Variables:

    ieta:iphi (ix:iy:iz), instantaneous luminosity, integrated luminosity


Info:

    to dump luminosity information, see https://github.com/amassiro/DumpLumi
    
    Actually no need, in new trees, "lumi" already dumped into the ttree

    
    
How to read:

    r00t draw.cxx\(\"Transparency/BlueLaser_2017_rereco_v2_newformat.root\",62,50,1\)
    r00t draw.cxx\(\"Transparency/BlueLaser_2017_rereco_v2_newformat.root\",21,120,0\)
