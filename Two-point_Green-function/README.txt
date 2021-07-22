In this folder you can find three Mathematica notebooks:

1-GME.nb:                   It calculate the bands and the modes of the photonic crystal slabs described in https://arxiv.org/abs/2107.00476 by using an implementations of the Guided-Mode expansion method.
                            Some calculations of this notebook are record in a .dat files to be used for the oder notebook. 
                            In this folder, you can found these .dat files for the case of a basis with parameters gx=9 and Ng=3. 
                            For other basis parameters, you have to record the new .dat files in order to use the following notebooks (2-kP.nb and 3-Green-Linear-Alcance.nb).
            
2-kP.nb:                    It use the GME results from the 1-GME.nb at the high symmetry points K and K' to implement the k.p approximation around these points. 
                            With this method, this notebook describe analytical the frequencies and modes for k-points near the Dirac point K(K').
                            As in the 1-GME.nb, 2-kP.nb record some .dat files that is used by the last notebook (3-Green-Linear-Alcance.nb).
            
3-Green-Linear-Alcance.nb:  It use the results from the two first notebook to build up the two-point Green function for frequencies close to the Dirac point frequency.
                            Using the Green function, it make a fit of the Green function as power-law decay with the distance between two homologouos points in different unit cells.
                            The fit is evaluated at positions in the whole unit cell and show the main results of the work in https://arxiv.org/abs/2107.00476
                           
You can find some comments in each notebook. Any additional questions do not hesitate to contact me by e-mail: epnavarro@unal.edu.co
