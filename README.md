<script>
<?xml version="1.0" encoding="utf-8" ?>
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
<xs:element name="Root">
<xs:complexType>
<xs:choice maxOccurs="unbounded">
<xs:element name="Thing" minOccurs="0" maxOccurs="unbounded">
<xs:complexType>
<xs:sequence>
<xs:element name="IDThing" type="xs:string" />
<xs:element name="Count_Thing" type="xs:int" />
</xs:sequence>
</xs:complexType>
</xs:element>
</xs:choice>
</xs:complexType>
</xs:element>
</xs:schema>
</script>
<?xml version="1.0" encoding="utf-8"?>
<Root xmlns="XSD1.xsd"> Справочник оборудования/приборов <!—обратите внимание на ссылку на xsd —> <br />

<Thing> <table border="1"> <tr>
<td>Код прибора</td>
<td>Название прибора</td>
<td><IDThing>Тип прибора</IDThing></td>
<td><IDThing>Дата производства</IDThing></td>
<td><IDThing>Материально
ответственное лицо</IDThing></td>
</tr>
<tr>
<td><Count_Thing>1</Count_Thing></td>
<td><IDThing>машина</IDThing></td>
<td><IDThing>механика</IDThing></td>
<td><IDThing>02.06.96</IDThing></td>
<td><IDThing>механики</IDThing></td>
</tr>
<tr>
<td><Count_Thing>2</Count_Thing></td>
<td><IDThing>пылисос</IDThing></td>
<td><IDThing>механика</IDThing></td>
<td><IDThing>25.06.14</IDThing></td>
<td><IDThing>изобретатели</IDThing></td>
</tr>
<tr>
<td><Count_Thing>3</Count_Thing></td>
<td><IDThing>фен</IDThing></td>
<td><IDThing>механика</IDThing></td>
<td><IDThing>05.11.12</IDThing></td>
<td><IDThing>изобретатели</IDThing></td>
</tr>
<tr>
<td><Count_Thing>4</Count_Thing></td>
<td><IDThing>миксер</IDThing></td>
<td><IDThing>механика</IDThing></td>
<td><IDThing>01.01.16</IDThing></td>
<td><IDThing>изобретатели</IDThing></td>
</tr>
<tr>
<td><Count_Thing>5</Count_Thing></td>
<td><IDThing>стол</IDThing></td>
<td><IDThing>мебель</IDThing></td>
<td><IDThing>04.05.11</IDThing></td>
<td><IDThing>конструкторщики</IDThing></td>
</tr>
</table>

</Thing>
</Root>
# Spravochnik
