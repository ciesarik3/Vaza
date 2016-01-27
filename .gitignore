// author: Roman Ciesarik 27.1.2016
// email:  roman9631@gmail.com



 #include "colors.inc"  
 #include "textures.inc"  
 #include "stones.inc"  
 
 global_settings{ assumed_gamma 1.0 }
#default{ finish{ ambient 0.1 diffuse 0.9 }} 
 
 
camera { location <-10, 20, -10>
         look_at 4
         angle 90
       }
  
background { color Gray50 }
light_source{<1500,2500,-2500> color White}

plane { <0, 1, 0>, 0
      pigment { checker color White, color Yellow }
      }   
   
torus { 4, 0.5  // major and minor radius     4,1
        pigment { Gold}   
      }

union{
  
    difference { 
       
        sphere {  <0, -0.5, >, 4.3
                 texture { pigment { color Gold }}
                }      
        
        cone { <0, 10, 0>, 6    
               <0, -2, >, 3   
               texture { T_Stone2 scale 4 }}
              }   
  
  
              
    difference { 
        
        sphere { <0, 4,0 >, 4.8
                texture {pigment { color Blue }}       
                }     
  
  
        cone { <0, 35, 0>, 4   // Center and radius of one end
               <0, -2, >, 3   // Center and radius of other end
               texture { pigment { color Gold }}
               }
              }     
  
    difference {  
    
        torus {   3, .6     // major and minor radius
                translate < 0, 9.7, 0> 
                pigment { Gold }  
                }   
   
   
        cone {  <0, 10, 0>, 3   // Center and radius of one end
                <0, 0,0 >, 4   // Center and radius of other end
                 texture { pigment { color Gold }}
               }   
              } 
  
  
    difference {    
        cone {  <0, 10, 0>, 3   // Center and radius of one end
                <0, 0,0 >, 4   // Center and radius of other end
                 texture { pigment { color Gold }}
              } 
                                   
       cone {   <0, 12, 0>, 2   // Center and radius of one end
                <0, -10,0 >, 1   // Center and radius of other end
                texture { pigment { color Gold }}  
              }
                 torus {   3.5, .6    
    translate < 0, 8.35, 0>       //9.8
    pigment { Gold }
            }    
              
                }
   torus {   3.5, 1.5    
    translate < 0, 5, 0>       //9.8
    pigment { Silver}
            } 
            
             
      difference {
   
   torus {   2.5, .5    
    translate < 0, 10.2, 0>       //9.8
    pigment { Silver }  
    
     }           
             
             
             
              sor {
    8,
    <0.0,  -0.5>,
    <3.0,   0.0>,
    <1.0,   0.2>,
    <0.5,   0.4>,
    <0.5,   4.0>,
    <1.0,   5.0>,
    <3.0,  10.0>,
    <4.0,  11.0>
    open
    texture {  pigment { color Black} } 
    translate < 0, 2, 0>       //9.8
  }    }
  
       }  
        
        
     sor {    
        6,
    <5,  0>,    
    <2,   4.0>,
    <4,   5.0>,
    <2.0,  10.0>,
    <4.0,  11.0> 
     <6.0,  12.0> 
  
    open
    texture {  pigment { color Green} } 
    translate < 0, 2, 0>       //9.8
  }  
      
         
