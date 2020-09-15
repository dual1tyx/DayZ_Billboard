# DayZ Billboard

Customisable billboard for DayZ from Arma 2 Sample Models
There are two types of boards the full-sized billboard and a 50% sized billboard.

The full sized one is created using the model in this snippet:

    class Land_Custom_Billboard: HouseNoDestruct {
    	scope=2;
    	model="DayZ_Billboard\billboard_trs.p3d";
    	hiddenSelections[]={"tex"};
    	hiddenSelectionsTextures[]={"DayZ_Billboard\Data\board_alkohol_co.paa"};
    };

The 50% one is created using the model in this snippet:

    class Land_Custom_Board: HouseNoDestruct {
    	scope=2;
    	model="DayZ_Billboard\board_trs.p3d";
    	hiddenSelections[]={"tex"};
    	hiddenSelectionsTextures[]={"DayZ_Billboard\Data\board_vodka_co.paa"};
    };

To apply a new texture create a .paa file matching the dimension of the default ones provided. Place in the Data/ folder and adjust the hiddenSelectionsTextures to fit. 