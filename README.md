# JSON-Format-in-Trdidium-niagara
Converting Values into JSON format without using JSON toolkit
In IOT world JSON is the one of the widlely used Data format.
One of my project required MQTT data establishment for cloud solution.
And the data format should be JSON.
Before this i tested and used MQTT for other solutions but without JSON.
so i started working around JSON format in Tridium niagara workbench
by using JSON Toolkit(Available in triidum niagara by default) i was able to create JSON format as required.
but when i tried to implement the same in JACE 8000 , it asked for Addtional License.it worked in Workbench because it have engineer version license.
Then started working on program (java script) to achive this.
it was challenging to bring the output as expected.but somwhow i was succefully achived that and implemented in site.
And this is not suitable for handling huge number of values , because need to work in script according to the number of values we are hanndling.
this method will be helpfull when we are handling multiple typical set of values or small number of value.
In my case i used Typical set of values ,
around 40 Energy meter with typically 2 values (POWER,ENERGY)
