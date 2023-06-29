Steps:

Download the software from the website [https://qgis.org/en/site/](URL).

You can download maps according to your needs from this link: [https://www.diva-gis.org/gdata](URL).

1) To add a new layer, use the "Vector Layer" option and choose a shapefile to work with.

![19](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/94409c5a-bc8e-415c-9537-6a0a7af1be26)

![1](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/d51d41cf-697e-4af6-85b4-51ee43572808)

![2](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/889f6f0c-b3dc-4356-899c-caefcac8d090)

![3](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/ba495565-f425-4b8f-9231-99c5807bb1c6)

4) Change the properties of the layer from the provided options.

![4](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/47f503e1-0792-465b-acf6-43cec76949a2)

![5](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/7703fcdc-edc5-4854-b608-8b68064848b2)

6) To add a new layer with coordinates, follow these steps:
  a) Go to the "Delimited Text Layer" option.
  b) Add the CSV file containing latitude, longitude, and optionally a Z-axis value. For example, if you want to analyze population in 3D, ensure the values are         either integers or decimals.

![6](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/382e9ef1-6aae-4f19-950d-75bdcdc06e83)

![7](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/8f9c1168-7e06-48e7-bcbb-41d49ff54b50)

![8](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/1c15eb58-57b1-4d10-93e9-e29aedd4f9ed)

![9](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/1075302b-c504-4d87-a5ca-67a076df625f)

![10](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/f90e83bc-c272-42d7-ac66-02984653f242)

11) To convert the delimited text layer into 3D, use the TIN interpolation method. Make sure the CRS is set to EPSG:4326, located in the bottom right corner.

![11](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/6e17c513-6d84-43c7-9845-b9e72f5114fe)

![12](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/850b5149-f845-4bd1-8794-d64a596048b8)

![13](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/9207907b-03db-4e2f-b05a-9e0692626ce6)

![14](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/fb269ef9-3b4c-4c95-8d69-9f5f2305d5e2)

![15](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/c3c31a0c-046b-47b9-80e6-1cc2e31d8452)

![16](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/d1ca164e-eb85-42c5-a994-89c86a1422ff)

![17](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/1e6d75b6-349a-47ad-ae16-764d78968d4d)

18) Change the CRS based on the screenshot provided. However, the choice of CRS depends on the type of data and the area you are working on. For example, if you are working with an India map and require a suitable 3D representation, select the appropriate CRS.

![18](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/b3c7adad-9a8f-454c-b3e8-40c7a5b03d2a)

![19](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/336d2d91-fa30-4681-b1f7-6f32ded5e594)

20) After completing the previous steps, be cautious with your data selection and choose accordingly. Then, go to Qgis2threejs to visualize the map in 3D. You can adjust the properties there to achieve your desired output. Make sure to install the Qgis2threejs plugin before proceeding.

![india](https://github.com/AaryanGiri/QGIS-Intern/assets/19299140/da9fa48b-7aa6-40ef-a5fb-f1e0534cb7fd)
