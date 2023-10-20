This database was inspired by one of Sydney's most popular events Sculpture by the Sea, 
held in 1997, which is a free exhibition with over 100 sculptures by artists from around the world. 
Most of the data in the project are not real, they are self-generated.

Official Website: https://sculpturebythesea.com

There're 6 main tables in the database which are Sculpture, Artist, Award, Material, Volunteer, Shift.
And there're three association tables between three many to many relationships, which are SculptureMaterial, SculptureArtist, ShiftVolunteer.

The relationship between Sculpture and Material, Shift and Volunteer, Sculpture and Artist are many to many.
One sculpture can use many materials, and one material can be used by many sculptures.
One shift with specific ShiftID can be matched with many volunteers, and one volunteer can have many shifts.
One sculpture can be designed by many artists, and one artist can design many sculptures.
