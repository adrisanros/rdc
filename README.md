<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<catalogue id="b0a7-8bc8-db26-e347" name="RDC Reinos del Caos: Demonios" revision="12" battleScribeVersion="2.03" authorName="Cordo" authorContact="leyendasenminiatura@gmail.com" authorUrl="http://www.leyendasenminiatura.com/" library="false" gameSystemId="fd97-5cfe-d46c-03c6" gameSystemRevision="6" xmlns="http://www.battlescribe.net/schema/catalogueSchema">
  <selectionEntries>
    <selectionEntry id="3ea4-be6a-29f5-bc8c" name="Carro flam�gero de Tzeentch (incineradores)" hidden="false" collective="false" import="true" type="unit">
      <profiles>
        <profile id="fb06-f15f-a2bf-5703" name="Carro flam�gero de Tzeentch" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
          <characteristics>
            <characteristic name="M" typeId="2d56-9cad-9242-37bd"/>
            <characteristic name="HA" typeId="c87b-b820-6a47-1354"/>
            <characteristic name="HP" typeId="8ab7-c800-6644-f5ec"/>
            <characteristic name="F" typeId="79c2-0368-3eed-76b4">4</characteristic>
            <characteristic name="R" typeId="30bd-8385-2b51-e039">4</characteristic>
            <characteristic name="H" typeId="a41f-60f6-2336-73ab">4</characteristic>
            <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f"/>
            <characteristic name="A" typeId="6b2b-37c4-6774-748b"/>
            <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3"/>
            <characteristic name="TSA" typeId="2532-2940-06ec-7a6e">5+</characteristic>
            <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Carro, Demonio, Caos, Tzeentch.</characteristic>
            <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705">3 (+1 si lleva un personaje)</characteristic>
          </characteristics>
        </profile>
      </profiles>
      <infoLinks>
        <infoLink id="4135-4cbf-7027-482f" name="Demonio" hidden="false" targetId="3b16-1038-ec5b-845b" type="rule"/>
        <infoLink id="23ff-3f38-103b-7864" name="Aura Demon�aca" hidden="false" targetId="6ee8-71c7-3d74-f8ff" type="rule"/>
        <infoLink id="c467-3a4e-3ee6-88e1" name="Dios del Caos" hidden="false" targetId="1358-d734-5293-f4cf" type="rule"/>
        <infoLink id="5d5e-b064-acd1-28ea" name="Inestabilidad Demon�aca" hidden="false" targetId="8c45-e9fd-1a51-f92c" type="rule"/>
        <infoLink id="fcf4-9bc5-a953-1b67" name="Marcas del Caos" hidden="false" targetId="e389-b085-6f21-2a58" type="rule"/>
        <infoLink id="6e44-5c91-991e-05c4" name="Volar" hidden="false" targetId="90d6-fe4d-a823-314b" type="rule"/>
        <infoLink id="967f-86d1-91b0-d191" name="Carro" hidden="false" targetId="1bd3-1808-aa0b-6883" type="rule"/>
        <infoLink id="ecc1-4982-93e0-5b48" name="Impactos por carga (1D6)" hidden="false" targetId="944f-4d13-dd5d-baa5" type="rule"/>
      </infoLinks>
      <categoryLinks>
        <categoryLink id="2163-66ea-c9ee-c946" name="New CategoryLink" hidden="false" targetId="184a-30ec-bf7c-b603" primary="true"/>
      </categoryLinks>
      <selectionEntries>
        <selectionEntry id="2216-0949-1cdf-6f45" name="Incineradores" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="2.0" percentValue="false" shared="false" includeChildSelections="false" includeChildForces="false" id="72f9-2f6a-c459-6098" type="min"/>
            <constraint field="selections" scope="parent" value="2.0" percentValue="false" shared="false" includeChildSelections="false" includeChildForces="false" id="5016-0810-f5b1-9ca6" type="max"/>
          </constraints>
          <profiles>
            <profile id="90f1-78ec-8f4a-bb85" name="Incinerador" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
              <characteristics>
                <characteristic name="M" typeId="2d56-9cad-9242-37bd"/>
                <characteristic name="HA" typeId="c87b-b820-6a47-1354">2</characteristic>
                <characteristic name="HP" typeId="8ab7-c800-6644-f5ec">4</characteristic>
                <characteristic name="F" typeId="79c2-0368-3eed-76b4">4</characteristic>
                <characteristic name="R" typeId="30bd-8385-2b51-e039"/>
                <characteristic name="H" typeId="a41f-60f6-2336-73ab"/>
                <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">4</characteristic>
                <characteristic name="A" typeId="6b2b-37c4-6774-748b">2</characteristic>
                <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">8</characteristic>
                <characteristic name="TSA" typeId="2532-2940-06ec-7a6e"/>
                <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Demonio, Caos, Tzeentch.</characteristic>
                <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705"/>
              </characteristics>
            </profile>
          </profiles>
          <infoLinks>
            <infoLink id="2993-f111-ba5e-95ee" name="Llamaradas de Tzeentch" hidden="false" targetId="ab40-e96e-7547-e566" type="rule"/>
          </infoLinks>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
        <selectionEntry id="0ba6-2f96-fbb8-9565" name="Aulladores" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="2.0" percentValue="false" shared="false" includeChildSelections="false" includeChildForces="false" id="78d3-2028-d53a-aa91" type="min"/>
            <constraint field="selections" scope="parent" value="2.0" percentValue="false" shared="false" includeChildSelections="false" includeChildForces="false" id="de05-d152-1378-2000" type="max"/>
          </constraints>
          <profiles>
            <profile id="94c1-6122-8826-bdf7" name="Aullador" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
              <characteristics>
                <characteristic name="M" typeId="2d56-9cad-9242-37bd">3</characteristic>
                <characteristic name="HA" typeId="c87b-b820-6a47-1354">3</characteristic>
                <characteristic name="HP" typeId="8ab7-c800-6644-f5ec"/>
                <characteristic name="F" typeId="79c2-0368-3eed-76b4">4</characteristic>
                <characteristic name="R" typeId="30bd-8385-2b51-e039"/>
                <characteristic name="H" typeId="a41f-60f6-2336-73ab"/>
                <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">4</characteristic>
                <characteristic name="A" typeId="6b2b-37c4-6774-748b">2</characteristic>
                <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">8</characteristic>
                <characteristic name="TSA" typeId="2532-2940-06ec-7a6e"/>
                <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Demonio, Caos, Tzeentch.</characteristic>
                <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705"/>
              </characteristics>
            </profile>
          </profiles>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
      </selectionEntries>
      <selectionEntryGroups>
        <selectionEntryGroup id="1ca5-5b26-3008-bb49" name="Marca del Caos" hidden="false" collective="false" import="true" defaultSelectionEntryId="497a-75e0-1a34-dd3c">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="4533-761f-f1bb-4919" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="4dab-5cc9-53f9-8443" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="497a-75e0-1a34-dd3c" name="Marca de Tzeentch" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="acbb-06c9-86ae-5f99" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="ed6e-dc46-40f7-0ef1" type="min"/>
              </constraints>
              <rules>
                <rule id="aeb5-da4d-da2f-4f27" name="Marca de Tzeentch" hidden="false">
                  <description>Sin efecto adicional.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
      </selectionEntryGroups>
      <costs>
        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="140.0"/>
      </costs>
    </selectionEntry>
    <selectionEntry id="2bda-36ba-1e6f-5812" name="Carro de la demencia de Slaanesh" hidden="false" collective="false" import="true" type="unit">
      <profiles>
        <profile id="de90-1626-1e50-3c67" name="Carro de la demencia de Slaanesh" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
          <characteristics>
            <characteristic name="M" typeId="2d56-9cad-9242-37bd"/>
            <characteristic name="HA" typeId="c87b-b820-6a47-1354"/>
            <characteristic name="HP" typeId="8ab7-c800-6644-f5ec"/>
            <characteristic name="F" typeId="79c2-0368-3eed-76b4">5</characteristic>
            <characteristic name="R" typeId="30bd-8385-2b51-e039">4</characteristic>
            <characteristic name="H" typeId="a41f-60f6-2336-73ab">4</characteristic>
            <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f"/>
            <characteristic name="A" typeId="6b2b-37c4-6774-748b"/>
            <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3"/>
            <characteristic name="TSA" typeId="2532-2940-06ec-7a6e">5+</characteristic>
            <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Carro, Demonio, Caos, Slaanesh</characteristic>
            <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705">4</characteristic>
          </characteristics>
        </profile>
      </profiles>
      <rules>
        <rule id="8b76-58aa-c243-9389" name="Aura de Slaanesh" hidden="false">
          <description>Todas las unidades y personajes enemigos en contacto peana con peana con uno o m�s Demonios con Aura de Slaanesh tienen un -1 a su Liderazgo, hasta un m�nimo de 2.</description>
        </rule>
        <rule id="07c1-1136-487d-fd51" name="Corceles de Slaanesh" hidden="false">
          <description>Los Corceles de Slaanesh tienen las reglas Ataque envenenado y Siempre ataca primero.</description>
        </rule>
      </rules>
      <infoLinks>
        <infoLink id="4c37-6387-9602-e4fc" name="Demonio" hidden="false" targetId="3b16-1038-ec5b-845b" type="rule"/>
        <infoLink id="51ac-c60d-c1f4-c3dc" name="Aura Demon�aca" hidden="false" targetId="6ee8-71c7-3d74-f8ff" type="rule"/>
        <infoLink id="5d9a-655c-0c40-65a4" name="Dios del Caos" hidden="false" targetId="1358-d734-5293-f4cf" type="rule"/>
        <infoLink id="8785-3b38-3193-8d9a" name="Inestabilidad Demon�aca" hidden="false" targetId="8c45-e9fd-1a51-f92c" type="rule"/>
        <infoLink id="7507-1141-d5f4-7c8e" name="Marcas del Caos" hidden="false" targetId="e389-b085-6f21-2a58" type="rule"/>
        <infoLink id="9b4e-c1ad-387c-7228" name="Carro" hidden="false" targetId="1bd3-1808-aa0b-6883" type="rule"/>
        <infoLink id="a9f1-38d2-8686-47e5" name="Impactos por carga (1D6+1)" hidden="false" targetId="2518-df58-89ad-82cb" type="rule"/>
      </infoLinks>
      <categoryLinks>
        <categoryLink id="9437-758c-5902-ef0b" name="New CategoryLink" hidden="false" targetId="102e-012c-5785-3354" primary="true"/>
      </categoryLinks>
      <selectionEntries>
        <selectionEntry id="f36a-b8fa-7766-88a6" name="Corceles de Slaanesh" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="2.0" percentValue="false" shared="false" includeChildSelections="false" includeChildForces="false" id="3f27-f809-716f-a416" type="min"/>
            <constraint field="selections" scope="parent" value="2.0" percentValue="false" shared="false" includeChildSelections="false" includeChildForces="false" id="351d-0346-e0f9-7288" type="max"/>
          </constraints>
          <profiles>
            <profile id="749c-ea88-14db-ef93" name="Corcel de Slaanesh" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
              <characteristics>
                <characteristic name="M" typeId="2d56-9cad-9242-37bd">25</characteristic>
                <characteristic name="HA" typeId="c87b-b820-6a47-1354">3</characteristic>
                <characteristic name="HP" typeId="8ab7-c800-6644-f5ec"/>
                <characteristic name="F" typeId="79c2-0368-3eed-76b4">3</characteristic>
                <characteristic name="R" typeId="30bd-8385-2b51-e039"/>
                <characteristic name="H" typeId="a41f-60f6-2336-73ab"/>
                <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">5</characteristic>
                <characteristic name="A" typeId="6b2b-37c4-6774-748b">1</characteristic>
                <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">8</characteristic>
                <characteristic name="TSA" typeId="2532-2940-06ec-7a6e"/>
                <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Demonio, Caos, Slaanesh</characteristic>
                <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705"/>
              </characteristics>
            </profile>
          </profiles>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
        <selectionEntry id="afea-30c5-cc9c-5ab1" name="Diablillas" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="2.0" percentValue="false" shared="false" includeChildSelections="false" includeChildForces="false" id="9929-cf89-0d65-cdc9" type="min"/>
            <constraint field="selections" scope="parent" value="2.0" percentValue="false" shared="false" includeChildSelections="false" includeChildForces="false" id="d9bf-eb39-f811-2020" type="max"/>
          </constraints>
          <profiles>
            <profile id="ca76-195d-c2a5-909a" name="Diablilla" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
              <characteristics>
                <characteristic name="M" typeId="2d56-9cad-9242-37bd"/>
                <characteristic name="HA" typeId="c87b-b820-6a47-1354">4</characteristic>
                <characteristic name="HP" typeId="8ab7-c800-6644-f5ec"/>
                <characteristic name="F" typeId="79c2-0368-3eed-76b4">4</characteristic>
                <characteristic name="R" typeId="30bd-8385-2b51-e039"/>
                <characteristic name="H" typeId="a41f-60f6-2336-73ab"/>
                <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">5</characteristic>
                <characteristic name="A" typeId="6b2b-37c4-6774-748b">2</characteristic>
                <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">8</characteristic>
                <characteristic name="TSA" typeId="2532-2940-06ec-7a6e"/>
                <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Demonio, Caos, Slaanesh</characteristic>
                <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705"/>
              </characteristics>
            </profile>
          </profiles>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
      </selectionEntries>
      <selectionEntryGroups>
        <selectionEntryGroup id="6e9c-9092-a15c-5415" name="Marca del Caos" hidden="false" collective="false" import="true" defaultSelectionEntryId="0978-ee7e-266c-fa47">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="ce41-505d-eecc-d471" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="429e-47e5-2dcc-d265" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="0978-ee7e-266c-fa47" name="Marca de Slaanesh" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="0607-1bb8-cfc5-110d" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="c0a0-a677-8843-0b6a" type="min"/>
              </constraints>
              <rules>
                <rule id="8642-c5ab-b93b-d4ac" name="Marca de Slaanesh" hidden="false">
                  <description>Sin efecto adicional.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
      </selectionEntryGroups>
      <costs>
        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="130.0"/>
      </costs>
    </selectionEntry>
    <selectionEntry id="79a4-76f6-534c-7290" name="Ca��n de cr�neos" hidden="false" collective="false" import="true" type="unit">
      <constraints>
        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="be75-3375-e9c1-d2ce" type="max"/>
      </constraints>
      <profiles>
        <profile id="e56b-8d63-68d4-ab6c" name="Ca��n de cr�neos" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
          <characteristics>
            <characteristic name="M" typeId="2d56-9cad-9242-37bd">18</characteristic>
            <characteristic name="HA" typeId="c87b-b820-6a47-1354">5</characteristic>
            <characteristic name="HP" typeId="8ab7-c800-6644-f5ec"/>
            <characteristic name="F" typeId="79c2-0368-3eed-76b4">5</characteristic>
            <characteristic name="R" typeId="30bd-8385-2b51-e039">5</characteristic>
            <characteristic name="H" typeId="a41f-60f6-2336-73ab">5</characteristic>
            <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">2</characteristic>
            <characteristic name="A" typeId="6b2b-37c4-6774-748b">2</characteristic>
            <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">8</characteristic>
            <characteristic name="TSA" typeId="2532-2940-06ec-7a6e">3+</characteristic>
            <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Carro, M�quina de guerra, Demonio, Caos, Khorne</characteristic>
            <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705">5</characteristic>
          </characteristics>
        </profile>
      </profiles>
      <rules>
        <rule id="6690-4de7-eaef-5b2f" name="Ca��n de cr�neos" hidden="false">
          <description>En disparo, trata el Ca��n de Cr�neos como un ca��n peque�o (m�ltiples 1D3, anula armaduras, puede disparar metralla) con las siguientes excepciones: tiene un alcance de 30 cm, Fuerza 8, los impactos del ca��n son Ataques flam�geros, usa el �ngulo de visi�n del Carro, puede mover y disparar (ya que el ca��n est� vivo) y si sale problemas afecta a toda la miniatura (si sale Destruido, se destruye todo el Ca��n de Cr�neos). </description>
        </rule>
        <rule id="bbcc-f4a5-483f-c9ae" name="Carro, furia asesina y frontal" hidden="false">
          <description>S�lo los Desangradores ganan el ataque extra (no el Ca��n), pero toda la miniatura se ve sujeta a las reglas de movimiento de la Furia Asesina.
Ten en cuenta que el Ca��n s�lo ataca por su frontal, como si fuera una bestia de tiro.</description>
        </rule>
      </rules>
      <infoLinks>
        <infoLink id="2177-fbf9-f037-9093" name="Demonio" hidden="false" targetId="3b16-1038-ec5b-845b" type="rule"/>
        <infoLink id="df42-2503-46b1-21e4" name="Objetivo grande" hidden="false" targetId="9e28-dc38-0f21-77f6" type="rule"/>
        <infoLink id="547b-d8ab-ffa5-4d52" name="Aura Demon�aca" hidden="false" targetId="6ee8-71c7-3d74-f8ff" type="rule"/>
        <infoLink id="d35f-ea6a-65b5-7619" name="Dios del Caos" hidden="false" targetId="1358-d734-5293-f4cf" type="rule"/>
        <infoLink id="4a2f-04f8-11ec-ea3f" name="Inestabilidad Demon�aca" hidden="false" targetId="8c45-e9fd-1a51-f92c" type="rule"/>
        <infoLink id="c04c-4064-a607-0967" name="Marcas del Caos" hidden="false" targetId="e389-b085-6f21-2a58" type="rule"/>
        <infoLink id="45f0-45e5-04a9-9118" name="Furia asesina" hidden="false" targetId="000a-cfde-6e79-aecb" type="rule"/>
        <infoLink id="da53-beb6-1143-03bb" name="Carro" hidden="false" targetId="1bd3-1808-aa0b-6883" type="rule"/>
        <infoLink id="0d64-fdf3-8626-f647" name="Impactos por carga (1D6+1)" hidden="false" targetId="2518-df58-89ad-82cb" type="rule"/>
        <infoLink id="092d-d07b-d093-8ae8" name="Resistencia a la magia 1" hidden="false" targetId="10ae-f386-2057-289d" type="rule"/>
      </infoLinks>
      <categoryLinks>
        <categoryLink id="05b4-1363-75fc-4ecd" name="New CategoryLink" hidden="false" targetId="184a-30ec-bf7c-b603" primary="true"/>
      </categoryLinks>
      <selectionEntries>
        <selectionEntry id="464e-5705-956c-544e" name="Desangradores" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="2.0" percentValue="false" shared="false" includeChildSelections="false" includeChildForces="false" id="0c41-1f93-141f-116d" type="min"/>
            <constraint field="selections" scope="parent" value="2.0" percentValue="false" shared="false" includeChildSelections="false" includeChildForces="false" id="4b93-0287-d765-acc6" type="max"/>
          </constraints>
          <profiles>
            <profile id="41d0-eac3-6bdb-55ff" name="Desangrador" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
              <characteristics>
                <characteristic name="M" typeId="2d56-9cad-9242-37bd"/>
                <characteristic name="HA" typeId="c87b-b820-6a47-1354">5</characteristic>
                <characteristic name="HP" typeId="8ab7-c800-6644-f5ec">0</characteristic>
                <characteristic name="F" typeId="79c2-0368-3eed-76b4">5</characteristic>
                <characteristic name="R" typeId="30bd-8385-2b51-e039"/>
                <characteristic name="H" typeId="a41f-60f6-2336-73ab"/>
                <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">4</characteristic>
                <characteristic name="A" typeId="6b2b-37c4-6774-748b">1</characteristic>
                <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">8</characteristic>
                <characteristic name="TSA" typeId="2532-2940-06ec-7a6e"/>
                <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Infanter�a, Demonio, Caos, Khorne</characteristic>
                <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705"/>
              </characteristics>
            </profile>
          </profiles>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
      </selectionEntries>
      <selectionEntryGroups>
        <selectionEntryGroup id="4175-67a9-9317-fb47" name="Marca del Caos" hidden="false" collective="false" import="true" defaultSelectionEntryId="1e67-8f54-add5-03f9">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="571a-ae99-bf64-1be5" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="46da-5d12-a519-32b2" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="1e67-8f54-add5-03f9" name="Marca de Khorne" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="4383-4a00-6012-6a12" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="89ec-4260-c315-5104" type="min"/>
              </constraints>
              <rules>
                <rule id="1d17-c501-d082-671b" name="Marca de Khorne" hidden="false">
                  <description>Sin efecto adicional.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
      </selectionEntryGroups>
      <costs>
        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="240.0"/>
      </costs>
    </selectionEntry>
    <selectionEntry id="42ec-1dd8-8847-38b2" name="Sapos de plaga" hidden="false" collective="false" import="true" type="unit">
      <profiles>
        <profile id="a496-0070-afa0-6694" name="Sapo de plaga" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
          <characteristics>
            <characteristic name="M" typeId="2d56-9cad-9242-37bd">15</characteristic>
            <characteristic name="HA" typeId="c87b-b820-6a47-1354">3</characteristic>
            <characteristic name="HP" typeId="8ab7-c800-6644-f5ec">3</characteristic>
            <characteristic name="F" typeId="79c2-0368-3eed-76b4">4</characteristic>
            <characteristic name="R" typeId="30bd-8385-2b51-e039">4</characteristic>
            <characteristic name="H" typeId="a41f-60f6-2336-73ab">3</characteristic>
            <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">1</characteristic>
            <characteristic name="A" typeId="6b2b-37c4-6774-748b">2</characteristic>
            <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">8</characteristic>
            <characteristic name="TSA" typeId="2532-2940-06ec-7a6e"/>
            <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Bestia monstruosa, Demonio, Caos, Nurgle.</characteristic>
            <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705">3</characteristic>
          </characteristics>
        </profile>
      </profiles>
      <infoLinks>
        <infoLink id="2a2c-0314-8be8-f539" name="Aura Demon�aca" hidden="false" targetId="6ee8-71c7-3d74-f8ff" type="rule"/>
        <infoLink id="4786-e6af-ba93-37d1" name="Demonio" hidden="false" targetId="3b16-1038-ec5b-845b" type="rule"/>
        <infoLink id="10e9-401d-e92d-bbac" name="Dios del Caos" hidden="false" targetId="1358-d734-5293-f4cf" type="rule"/>
        <infoLink id="1d4b-b1ae-8357-2c06" name="Inestabilidad Demon�aca" hidden="false" targetId="8c45-e9fd-1a51-f92c" type="rule"/>
        <infoLink id="ba47-4d03-876c-49aa" name="Marcas del Caos" hidden="false" targetId="e389-b085-6f21-2a58" type="rule"/>
        <infoLink id="cefc-3a3e-522f-74ff" name="Ataques envenenados (6+)" hidden="false" targetId="d77c-34cb-f94c-aee1" type="rule"/>
      </infoLinks>
      <categoryLinks>
        <categoryLink id="7ab6-3bdc-e892-25bd" name="New CategoryLink" hidden="false" targetId="102e-012c-5785-3354" primary="true"/>
      </categoryLinks>
      <selectionEntries>
        <selectionEntry id="7aea-caed-49eb-00ab" name="Sapos de plaga" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="3.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="5e76-710c-7f5b-a33e" type="min"/>
          </constraints>
          <selectionEntryGroups>
            <selectionEntryGroup id="93a3-2bfe-751e-4018" name="Armas" hidden="false" collective="false" import="true" defaultSelectionEntryId="fb0e-23c3-9cf3-4858">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="f68c-4011-5996-0795" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="921b-4be3-49d5-2518" type="min"/>
              </constraints>
              <selectionEntries>
                <selectionEntry id="fb0e-23c3-9cf3-4858" name="Arma de mano" hidden="false" collective="true" import="true" type="upgrade">
                  <constraints>
                    <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="c9cc-70e2-8617-156f" type="max"/>
                    <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="1ece-c335-bb3a-b074" type="min"/>
                  </constraints>
                  <infoLinks>
                    <infoLink id="2580-e53d-019e-0ba8" name="Arma de mano" hidden="false" targetId="4645-41a2-83c2-d8bc" type="profile"/>
                  </infoLinks>
                  <costs>
                    <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
                  </costs>
                </selectionEntry>
              </selectionEntries>
            </selectionEntryGroup>
          </selectionEntryGroups>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="32.0"/>
          </costs>
        </selectionEntry>
      </selectionEntries>
      <selectionEntryGroups>
        <selectionEntryGroup id="e5ed-4df2-d13b-b9e1" name="Marca del Caos" hidden="false" collective="false" import="true" defaultSelectionEntryId="43a7-6a77-811e-9ea2">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="3574-7604-74b3-e06f" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="9667-ba58-e4e9-b3ca" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="43a7-6a77-811e-9ea2" name="Marca de Nurgle" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="c7ad-765e-dd0e-2965" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="8baf-8f74-bf89-8e4b" type="min"/>
              </constraints>
              <rules>
                <rule id="2c15-03a1-8038-0cb9" name="Marca de Nurgle" hidden="false">
                  <description>Sin efecto adicional.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
      </selectionEntryGroups>
      <costs>
        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
      </costs>
    </selectionEntry>
    <selectionEntry id="5d76-43e7-4ed6-8006" name="Z�nganos de plaga" hidden="false" collective="false" import="true" type="unit">
      <profiles>
        <profile id="13f9-acf7-d0c2-cf62" name="Z�ngano de plaga" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
          <characteristics>
            <characteristic name="M" typeId="2d56-9cad-9242-37bd">3</characteristic>
            <characteristic name="HA" typeId="c87b-b820-6a47-1354">4</characteristic>
            <characteristic name="HP" typeId="8ab7-c800-6644-f5ec">0</characteristic>
            <characteristic name="F" typeId="79c2-0368-3eed-76b4">4</characteristic>
            <characteristic name="R" typeId="30bd-8385-2b51-e039">5</characteristic>
            <characteristic name="H" typeId="a41f-60f6-2336-73ab">2</characteristic>
            <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">3</characteristic>
            <characteristic name="A" typeId="6b2b-37c4-6774-748b">3</characteristic>
            <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">8</characteristic>
            <characteristic name="TSA" typeId="2532-2940-06ec-7a6e">6+</characteristic>
            <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Caballer�a monstruosa, Demonio, Caos, Nurgle.</characteristic>
            <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705">2</characteristic>
          </characteristics>
        </profile>
        <profile id="2eed-9559-14ee-8c58" name="Propagador de plaga" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
          <characteristics>
            <characteristic name="M" typeId="2d56-9cad-9242-37bd">15</characteristic>
            <characteristic name="HA" typeId="c87b-b820-6a47-1354">4</characteristic>
            <characteristic name="HP" typeId="8ab7-c800-6644-f5ec">0</characteristic>
            <characteristic name="F" typeId="79c2-0368-3eed-76b4">4</characteristic>
            <characteristic name="R" typeId="30bd-8385-2b51-e039">5</characteristic>
            <characteristic name="H" typeId="a41f-60f6-2336-73ab">2</characteristic>
            <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">3</characteristic>
            <characteristic name="A" typeId="6b2b-37c4-6774-748b">4</characteristic>
            <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">8</characteristic>
            <characteristic name="TSA" typeId="2532-2940-06ec-7a6e">6+</characteristic>
            <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Caballer�a monstruosa, Demonio, Caos, Nurgle.</characteristic>
            <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705">2</characteristic>
          </characteristics>
        </profile>
      </profiles>
      <rules>
        <rule id="fbd7-36b9-a118-8c1d" name="Nube de moscas" hidden="false">
          <description>Toda unidad o miniatura enemiga, mientras est� en contacto peana con peana con una o m�s miniaturas con Nube de Moscas, tiene un penalizador de -1 a todas sus tiradas para impactar en combate cuerpo a cuerpo. Ten en cuenta que el penalizador es aplicado a cada miniatura en contacto aunque no dirija sus ataques a una miniatura con Nube de Moscas. Las miniaturas con Nube de moscas son inmunes a las Nubes de moscas enemigas (�est�n acostumbrados a las moscas!).</description>
        </rule>
        <rule id="7e15-b595-a84b-558b" name="Caballer�a monstruosa" hidden="false">
          <description>Son caballer�a voladora.</description>
        </rule>
        <rule id="b3ae-fc31-c141-7d5c" name="Torpes" hidden="false">
          <description>Caballer�a voladora, pero vuela 38cm en vez de 50cm.</description>
        </rule>
      </rules>
      <infoLinks>
        <infoLink id="3757-24dd-994d-700e" name="Demonio" hidden="false" targetId="3b16-1038-ec5b-845b" type="rule"/>
        <infoLink id="eef7-e8f5-ba18-5583" name="Aura Demon�aca" hidden="false" targetId="6ee8-71c7-3d74-f8ff" type="rule"/>
        <infoLink id="0adb-f23d-2afc-36df" name="Dios del Caos" hidden="false" targetId="1358-d734-5293-f4cf" type="rule"/>
        <infoLink id="f655-ef6d-e6ea-bd9d" name="Inestabilidad Demon�aca" hidden="false" targetId="8c45-e9fd-1a51-f92c" type="rule"/>
        <infoLink id="b1f9-81c8-f84f-ec84" name="Marcas del Caos" hidden="false" targetId="e389-b085-6f21-2a58" type="rule"/>
        <infoLink id="72bd-b978-4cdf-c7bd" name="Unidad voladora" hidden="false" targetId="3c95-16c8-fddf-93e0" type="rule"/>
        <infoLink id="ac5f-93b8-c2ef-3787" name="Ataques envenenados (6+)" hidden="false" targetId="d77c-34cb-f94c-aee1" type="rule"/>
      </infoLinks>
      <categoryLinks>
        <categoryLink id="c6e2-4144-18da-8425" name="New CategoryLink" hidden="false" targetId="184a-30ec-bf7c-b603" primary="true"/>
      </categoryLinks>
      <selectionEntries>
        <selectionEntry id="5fc7-0372-9f81-e20e" name="Z�nganos de plaga" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="3.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="d2b3-26d0-5ea3-4eff" type="min"/>
          </constraints>
          <selectionEntryGroups>
            <selectionEntryGroup id="da20-07c6-19bc-ae93" name="Armas" hidden="false" collective="false" import="true" defaultSelectionEntryId="75f2-a59b-b205-d316">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="dfc2-6850-ab15-90e3" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="58ce-bdb1-361e-fa32" type="min"/>
              </constraints>
              <selectionEntries>
                <selectionEntry id="75f2-a59b-b205-d316" name="Arma de mano" hidden="false" collective="true" import="true" type="upgrade">
                  <constraints>
                    <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="7330-2f1c-7e43-f25c" type="max"/>
                    <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="e87f-f155-b29d-f8c1" type="min"/>
                  </constraints>
                  <infoLinks>
                    <infoLink id="7a39-4f18-913b-e74b" name="Arma de mano" hidden="false" targetId="4645-41a2-83c2-d8bc" type="profile"/>
                  </infoLinks>
                  <costs>
                    <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
                  </costs>
                </selectionEntry>
              </selectionEntries>
            </selectionEntryGroup>
          </selectionEntryGroups>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="60.0"/>
          </costs>
        </selectionEntry>
        <selectionEntry id="582b-8371-665f-4600" name="Grupo de mando" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="9ba9-a656-4dd8-cb9b" type="max"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="e6d8-01f3-acb5-1a73" name="Propagador de plaga" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="2490-ec16-14d4-314e" type="max"/>
              </constraints>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="20.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="6e71-c90d-b99f-458d" name="Portaestandarte" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="238f-bc86-ea01-2de3" type="max"/>
              </constraints>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="20.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="3e49-c3f1-3cbb-c904" name="M�sico" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="0cf5-b322-3afe-538f" type="max"/>
              </constraints>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="10.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
      </selectionEntries>
      <selectionEntryGroups>
        <selectionEntryGroup id="e78c-2af5-276c-8b70" name="Marca del Caos" hidden="false" collective="false" import="true" defaultSelectionEntryId="cbc5-2198-79e9-08d9">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="d1be-1f60-6adb-69eb" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="425b-3ad9-9b4c-35c9" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="cbc5-2198-79e9-08d9" name="Marca de Nurgle" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="ade2-4782-0533-0ed4" type="max"/>
              </constraints>
              <rules>
                <rule id="9902-a9e8-8aab-228f" name="Marca de Nurgle" hidden="false">
                  <description>Sin efecto adicional.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
      </selectionEntryGroups>
      <costs>
        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
      </costs>
    </selectionEntry>
    <selectionEntry id="777c-a9a7-10fa-96ae" name="Aplastador de almas" hidden="false" collective="false" import="true" type="unit">
      <constraints>
        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="accb-628c-d5f2-f381" type="max"/>
      </constraints>
      <profiles>
        <profile id="d8bf-d100-ca42-7775" name="Aplastador de almas" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
          <characteristics>
            <characteristic name="M" typeId="2d56-9cad-9242-37bd">18</characteristic>
            <characteristic name="HA" typeId="c87b-b820-6a47-1354">3</characteristic>
            <characteristic name="HP" typeId="8ab7-c800-6644-f5ec">3</characteristic>
            <characteristic name="F" typeId="79c2-0368-3eed-76b4">6</characteristic>
            <characteristic name="R" typeId="30bd-8385-2b51-e039">6</characteristic>
            <characteristic name="H" typeId="a41f-60f6-2336-73ab">6</characteristic>
            <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">3</characteristic>
            <characteristic name="A" typeId="6b2b-37c4-6774-748b">4</characteristic>
            <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">8</characteristic>
            <characteristic name="TSA" typeId="2532-2940-06ec-7a6e">4+</characteristic>
            <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Monstruo, Demonio, Caos</characteristic>
            <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705">6</characteristic>
          </characteristics>
        </profile>
      </profiles>
      <rules>
        <rule id="e5e5-d44b-e42e-3919" name="Garras mec�nicas" hidden="false">
          <description>Arma de mano. El Aplastador de Almas puede intentar agarrar y aplastar algo con sus garras mec�nicas. Al inicio de cada fase de combate en la que participe, elige una miniatura enemiga en contacto peana con peana (sea del tipo que sea, incluso un Monstruo). La miniatura objetivo debe hacer un chequeo de Iniciativa para evitar ser agarrada. Si falla el chequeo, los ataques que el Aplastador asigne a esa miniatura (puede atacar a otra si quiere) en esa fase de combate impactar�n autom�ticamente.</description>
        </rule>
        <rule id="9815-4950-1c08-298c" name="Ca��n (metralla)" hidden="false">
          <description>El Aplastador de Almas puede disparar cada turno un ataque de Metralla como si fuera un Ca��n, con la salvedad de que puede mover y disparar (no marchar y disparar). Si causa Problemas, afecta al ca��n (si queda destruido, se destruye el ca��n, no el Aplastador).</description>
        </rule>
      </rules>
      <infoLinks>
        <infoLink id="d465-ca5b-af4a-4ae2" name="Demonio" hidden="false" targetId="3b16-1038-ec5b-845b" type="rule"/>
        <infoLink id="27dd-6e39-3613-68f5" name="Objetivo grande" hidden="false" targetId="9e28-dc38-0f21-77f6" type="rule"/>
        <infoLink id="efe3-ada7-ad55-bf4c" name="Aura Demon�aca" hidden="false" targetId="6ee8-71c7-3d74-f8ff" type="rule"/>
        <infoLink id="d69f-e225-47ec-838d" name="Dios del Caos" hidden="false" targetId="1358-d734-5293-f4cf" type="rule"/>
        <infoLink id="1f0d-4b38-8c9c-72ee" name="Inestabilidad Demon�aca" hidden="false" targetId="8c45-e9fd-1a51-f92c" type="rule"/>
        <infoLink id="21a5-70e3-678f-d921" name="Marcas del Caos" hidden="false" targetId="e389-b085-6f21-2a58" type="rule"/>
        <infoLink id="f779-76d2-c66c-8bb9" name="Terror" hidden="false" targetId="31ab-3ff3-e34f-baac" type="rule"/>
      </infoLinks>
      <categoryLinks>
        <categoryLink id="3d84-325c-1612-0e47" name="New CategoryLink" hidden="false" targetId="184a-30ec-bf7c-b603" primary="true"/>
      </categoryLinks>
      <selectionEntryGroups>
        <selectionEntryGroup id="9b9c-13ab-d52c-c447" name="Marca del Caos" hidden="false" collective="false" import="true" defaultSelectionEntryId="3b10-84dc-8999-bbfb">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="4451-1443-1cf2-2587" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="3235-ea8b-e8d8-7c73" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="3b10-84dc-8999-bbfb" name="Marca del Caos Absoluto" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="2143-4baf-3356-5058" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="4aa0-ea03-74bf-f19e" type="min"/>
              </constraints>
              <rules>
                <rule id="da20-7907-588d-b03f" name="Marca del Caos Absoluto" hidden="false">
                  <description>Sin efecto adicional.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
      </selectionEntryGroups>
      <costs>
        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="275.0"/>
      </costs>
    </selectionEntry>
    <selectionEntry id="d9ef-d181-015f-d2f5" name="Desollador infernal de Slaanesh" hidden="false" collective="false" import="true" type="unit">
      <profiles>
        <profile id="b812-688f-e8fc-37db" name="Desollador infernal" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
          <characteristics>
            <characteristic name="M" typeId="2d56-9cad-9242-37bd"/>
            <characteristic name="HA" typeId="c87b-b820-6a47-1354"/>
            <characteristic name="HP" typeId="8ab7-c800-6644-f5ec"/>
            <characteristic name="F" typeId="79c2-0368-3eed-76b4">5</characteristic>
            <characteristic name="R" typeId="30bd-8385-2b51-e039">4</characteristic>
            <characteristic name="H" typeId="a41f-60f6-2336-73ab">4</characteristic>
            <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f"/>
            <characteristic name="A" typeId="6b2b-37c4-6774-748b"/>
            <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3"/>
            <characteristic name="TSA" typeId="2532-2940-06ec-7a6e">5+</characteristic>
            <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Carro, Demonio, Caos, Slaanesh.</characteristic>
            <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705">4</characteristic>
          </characteristics>
        </profile>
      </profiles>
      <rules>
        <rule id="67be-119b-1ba2-90dc" name="Aura de Slaanesh" hidden="false">
          <description>Todas las unidades y personajes enemigos en contacto peana con peana con uno o m�s Demonios con Aura de Slaanesh tienen un -1 a su Liderazgo, hasta un m�nimo de 2.</description>
        </rule>
        <rule id="803f-933d-a88a-5356" name="Corceles de Slaanesh" hidden="false">
          <description>Los Corceles de Slaanesh tienen las reglas Ataque envenenado y Siempre ataca primero.</description>
        </rule>
        <rule id="a49a-b31c-c429-b7a4" name="Desollador" hidden="false">
          <description>Trata el Desollador como un carro a todos los efectos (incluyendo los 1D6+1 impactos por carga). Adem�s, despu�s de realizar los ataques de ambos bandos (incluidas las armas a dos manos y las miniaturas que siempre atacan �ltimo) pero antes de calcular el resultado del combate, y siempre que el Desollador no haya sido aniquilado (por ejemplo por una herida de F7 o superior) el Desollador hace 1D6 impactos de su Fuerza (F5). Estos impactos son adicionales a los impactos por carga y cuentan para la Resoluci�n de Combate.</description>
        </rule>
      </rules>
      <infoLinks>
        <infoLink id="15a4-9d01-541d-5b6e" name="Demonio" hidden="false" targetId="3b16-1038-ec5b-845b" type="rule"/>
        <infoLink id="2dd3-c245-7677-6d80" name="Aura Demon�aca" hidden="false" targetId="6ee8-71c7-3d74-f8ff" type="rule"/>
        <infoLink id="9dfe-4c51-10ca-0d37" name="Dios del Caos" hidden="false" targetId="1358-d734-5293-f4cf" type="rule"/>
        <infoLink id="56d9-628d-c941-cb9c" name="Inestabilidad Demon�aca" hidden="false" targetId="8c45-e9fd-1a51-f92c" type="rule"/>
        <infoLink id="6efb-c6d5-9565-2381" name="Marcas del Caos" hidden="false" targetId="e389-b085-6f21-2a58" type="rule"/>
        <infoLink id="3552-580a-63a6-d788" name="Carro" hidden="false" targetId="1bd3-1808-aa0b-6883" type="rule"/>
        <infoLink id="4ccb-e129-60aa-e303" name="Impactos por carga (1D6+1)" hidden="false" targetId="2518-df58-89ad-82cb" type="rule"/>
      </infoLinks>
      <categoryLinks>
        <categoryLink id="5a42-8077-cc51-477d" name="New CategoryLink" hidden="false" targetId="184a-30ec-bf7c-b603" primary="true"/>
      </categoryLinks>
      <selectionEntries>
        <selectionEntry id="b6ab-2c3a-24ca-d112" name="Diablillas" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="3.0" percentValue="false" shared="false" includeChildSelections="false" includeChildForces="false" id="137b-b31d-fdbe-87e1" type="min"/>
            <constraint field="selections" scope="parent" value="3.0" percentValue="false" shared="false" includeChildSelections="false" includeChildForces="false" id="ec42-db5b-e0c3-1f55" type="max"/>
          </constraints>
          <profiles>
            <profile id="55fd-cdf5-f25d-b809" name="Diablilla" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
              <characteristics>
                <characteristic name="M" typeId="2d56-9cad-9242-37bd"/>
                <characteristic name="HA" typeId="c87b-b820-6a47-1354">4</characteristic>
                <characteristic name="HP" typeId="8ab7-c800-6644-f5ec"/>
                <characteristic name="F" typeId="79c2-0368-3eed-76b4">4</characteristic>
                <characteristic name="R" typeId="30bd-8385-2b51-e039"/>
                <characteristic name="H" typeId="a41f-60f6-2336-73ab"/>
                <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">5</characteristic>
                <characteristic name="A" typeId="6b2b-37c4-6774-748b">2</characteristic>
                <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">8</characteristic>
                <characteristic name="TSA" typeId="2532-2940-06ec-7a6e"/>
                <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Infanter�a, Demonio, Caos, Slaanesh.</characteristic>
                <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705"/>
              </characteristics>
            </profile>
          </profiles>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
        <selectionEntry id="441a-3f0c-7aa7-d818" name="Corceles de Slaanesh" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="2.0" percentValue="false" shared="false" includeChildSelections="false" includeChildForces="false" id="46fc-6be7-f98b-1a19" type="min"/>
            <constraint field="selections" scope="parent" value="2.0" percentValue="false" shared="false" includeChildSelections="false" includeChildForces="false" id="1fa7-a1f9-9b9a-54b1" type="max"/>
          </constraints>
          <profiles>
            <profile id="3d7f-59eb-0f5e-3ade" name="Corcel de Slaanesh" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
              <characteristics>
                <characteristic name="M" typeId="2d56-9cad-9242-37bd">25</characteristic>
                <characteristic name="HA" typeId="c87b-b820-6a47-1354">3</characteristic>
                <characteristic name="HP" typeId="8ab7-c800-6644-f5ec"/>
                <characteristic name="F" typeId="79c2-0368-3eed-76b4">3</characteristic>
                <characteristic name="R" typeId="30bd-8385-2b51-e039"/>
                <characteristic name="H" typeId="a41f-60f6-2336-73ab"/>
                <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">5</characteristic>
                <characteristic name="A" typeId="6b2b-37c4-6774-748b">1</characteristic>
                <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">8</characteristic>
                <characteristic name="TSA" typeId="2532-2940-06ec-7a6e"/>
                <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Demonio, Caos, Slaanesh.</characteristic>
                <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705"/>
              </characteristics>
            </profile>
          </profiles>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
      </selectionEntries>
      <selectionEntryGroups>
        <selectionEntryGroup id="74dd-a6c4-deaf-9d70" name="Marca del Caos" hidden="false" collective="false" import="true" defaultSelectionEntryId="6b78-fa13-0264-60a3">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="2af8-34fe-0efd-7c9a" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="64f7-0eaf-19b2-a2ec" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="6b78-fa13-0264-60a3" name="Marca de Slaanesh" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="65b6-819b-989a-d47d" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="60a2-6ebd-c4c9-484c" type="min"/>
              </constraints>
              <rules>
                <rule id="d4c8-01f1-11f9-3c52" name="Marca de Slaanesh" hidden="false">
                  <description>Sin efecto adicional.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
      </selectionEntryGroups>
      <costs>
        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="185.0"/>
      </costs>
    </selectionEntry>
    <selectionEntry id="d869-7130-7fcd-e569" name="Devorador de almas (ocupa opci�n extra de h�roe y de singular)" hidden="false" collective="false" import="true" type="model">
      <profiles>
        <profile id="29cd-16b8-62f8-d089" name="Devorador de almas" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
          <characteristics>
            <characteristic name="M" typeId="2d56-9cad-9242-37bd">15</characteristic>
            <characteristic name="HA" typeId="c87b-b820-6a47-1354">10</characteristic>
            <characteristic name="HP" typeId="8ab7-c800-6644-f5ec">0</characteristic>
            <characteristic name="F" typeId="79c2-0368-3eed-76b4">6 (+1)</characteristic>
            <characteristic name="R" typeId="30bd-8385-2b51-e039">6</characteristic>
            <characteristic name="H" typeId="a41f-60f6-2336-73ab">7</characteristic>
            <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">10</characteristic>
            <characteristic name="A" typeId="6b2b-37c4-6774-748b">7</characteristic>
            <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">9</characteristic>
            <characteristic name="TSA" typeId="2532-2940-06ec-7a6e">4+</characteristic>
            <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Monstruo, Demonio, Caos, Khorne</characteristic>
            <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705">7</characteristic>
          </characteristics>
        </profile>
      </profiles>
      <infoLinks>
        <infoLink id="8da4-837a-e361-1c04" name="Aura Demon�aca" hidden="false" targetId="6ee8-71c7-3d74-f8ff" type="rule"/>
        <infoLink id="c4d2-788b-723a-8296" name="Terror" hidden="false" targetId="31ab-3ff3-e34f-baac" type="rule"/>
        <infoLink id="4174-6730-c85e-e1c8" name="Volar" hidden="false" targetId="90d6-fe4d-a823-314b" type="rule"/>
        <infoLink id="3be2-9db6-3d69-a6e2" name="Objetivo grande" hidden="false" targetId="9e28-dc38-0f21-77f6" type="rule"/>
        <infoLink id="daa6-84b3-89bd-fbf4" name="Furia asesina" hidden="false" targetId="000a-cfde-6e79-aecb" type="rule"/>
        <infoLink id="a056-1b77-37d7-0dab" name="Demonio" hidden="false" targetId="3b16-1038-ec5b-845b" type="rule"/>
        <infoLink id="f03d-aeda-22da-8af6" name="Dios del Caos" hidden="false" targetId="1358-d734-5293-f4cf" type="rule"/>
        <infoLink id="a9f7-1d69-1006-c13c" name="General demon�aco" hidden="false" targetId="fdbe-5f7a-4255-58c7" type="rule"/>
        <infoLink id="fbcc-ed19-4832-cbef" name="Inestabilidad Demon�aca" hidden="false" targetId="8c45-e9fd-1a51-f92c" type="rule"/>
        <infoLink id="af1c-b344-7a8e-d054" name="Marcas del Caos" hidden="false" targetId="e389-b085-6f21-2a58" type="rule"/>
        <infoLink id="604b-6e8d-9c42-4f24" name="Personajes y unidades" hidden="false" targetId="c927-071c-5329-89c9" type="rule"/>
        <infoLink id="8864-2ce1-b61c-1903" name="Resistencia a la magia 2" hidden="false" targetId="aa75-339e-8dd5-7203" type="rule"/>
      </infoLinks>
      <categoryLinks>
        <categoryLink id="a87c-cd23-03a8-5168" name="New CategoryLink" hidden="false" targetId="9769-7233-6405-675e" primary="true"/>
        <categoryLink id="a9ae-9dc9-a328-5119" name="New CategoryLink" hidden="false" targetId="c647-4209-4e6c-206a" primary="false"/>
        <categoryLink id="f71c-ae65-a4d5-d6d5" name="New CategoryLink" hidden="false" targetId="184a-30ec-bf7c-b603" primary="false"/>
      </categoryLinks>
      <selectionEntries>
        <selectionEntry id="854b-ac0e-276e-3da4" name="Objetos m�gicos" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="e278-3daa-90f3-dd5e" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="4184-e035-da57-0738" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="dc20-f1ad-6cd8-7e1b" name="Armadura de Khorne" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="roster" value="1.0" percentValue="false" shared="true" includeChildSelections="true" includeChildForces="false" id="e3e5-c669-a4dd-dcdc" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="d4d5-8dcc-b220-1c51" type="min"/>
              </constraints>
              <profiles>
                <profile id="58f3-5348-1488-a3e0" name="Armadura de Khorne" hidden="false" typeId="7e35-c20a-e9e9-6dad" typeName="Talism�n">
                  <characteristics>
                    <characteristic name="Protecci�n" typeId="9f41-c15e-1f5f-9d01">Tirada de salvaci�n por armadura de 4+. Esta tirada de salvaci�n no se acumula a la tirada que ya tuviera de por s�, por ejemplo un Heraldo tiene una tirada de salvaci�n por armadura de 6+, con Armadura de Khorne ser�a de 4+ (no se “sumar�a”).</characteristic>
                  </characteristics>
                </profile>
              </profiles>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="03e9-5575-49bc-d195" name="Hacha de Khorne" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="roster" value="1.0" percentValue="false" shared="true" includeChildSelections="true" includeChildForces="false" id="2a44-28fb-9ea5-470f" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="98a7-f678-52a8-1e8b" type="min"/>
              </constraints>
              <profiles>
                <profile id="4807-8b6c-f5c8-53e1" name="Hacha de Khorne" hidden="false" typeId="7e35-c20a-e9e9-6dad" typeName="Talism�n">
                  <characteristics>
                    <characteristic name="Protecci�n" typeId="9f41-c15e-1f5f-9d01">Golpe letal. Un Demonio con esta recompensa no puede elegir Arma infernal.</characteristic>
                  </characteristics>
                </profile>
              </profiles>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="a38c-c550-e08a-8830" name="Poder de Khorne" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="roster" value="1.0" percentValue="false" shared="true" includeChildSelections="true" includeChildForces="false" id="068e-0ccb-e12f-f8a9" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="b457-849a-5f64-319d" type="min"/>
              </constraints>
              <profiles>
                <profile id="5356-3db5-babb-22f3" name="Poder de Khorne" hidden="false" typeId="7e35-c20a-e9e9-6dad" typeName="Talism�n">
                  <characteristics>
                    <characteristic name="Protecci�n" typeId="9f41-c15e-1f5f-9d01">El Demonio tiene F+1. </characteristic>
                  </characteristics>
                </profile>
              </profiles>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
        <selectionEntry id="8139-1738-12ab-b2b1" name="Ocupa una opci�n de comandante, una de h�roe y una de unidad singular" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="30a5-f6af-d56e-7179" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="6ab7-2af1-d762-642b" type="min"/>
          </constraints>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
      </selectionEntries>
      <selectionEntryGroups>
        <selectionEntryGroup id="b9c2-22c4-93b0-e971" name="Armas" hidden="false" collective="false" import="true" defaultSelectionEntryId="2ec6-2c83-f28a-ccfa">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="d701-1f89-ea09-19fd" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="4d49-4d7f-e1dd-e315" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="2ec6-2c83-f28a-ccfa" name="Arma de mano" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="fe39-988c-1ebf-6da3" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="bcda-0e31-0173-0526" type="min"/>
              </constraints>
              <infoLinks>
                <infoLink id="17aa-27b2-3909-7f43" name="Arma de mano" hidden="false" targetId="4645-41a2-83c2-d8bc" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="d128-50b3-7b15-ee3c" name="Marca del Caos" hidden="false" collective="false" import="true" defaultSelectionEntryId="566e-f159-a2b1-6f64">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="525a-8401-edfd-a184" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="4ece-a5f9-266b-e041" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="566e-f159-a2b1-6f64" name="Marca de Khorne" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="3c53-9207-b6dc-ce2b" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="471d-33a6-46c9-2612" type="min"/>
              </constraints>
              <rules>
                <rule id="0461-1ef7-3134-7cfc" name="Marca de Khorne" hidden="false">
                  <description>Sin efecto adicional.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
      </selectionEntryGroups>
      <costs>
        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="650.0"/>
      </costs>
    </selectionEntry>
    <selectionEntry id="612e-cb7e-0c79-bde2" name="Gran inmundicia (ocupa opci�n extra de h�roe y de singular)" hidden="false" collective="false" import="true" type="model">
      <profiles>
        <profile id="d46d-3884-7d75-9dda" name="Gran inmundicia" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
          <characteristics>
            <characteristic name="M" typeId="2d56-9cad-9242-37bd">10</characteristic>
            <characteristic name="HA" typeId="c87b-b820-6a47-1354">8</characteristic>
            <characteristic name="HP" typeId="8ab7-c800-6644-f5ec">0</characteristic>
            <characteristic name="F" typeId="79c2-0368-3eed-76b4">6</characteristic>
            <characteristic name="R" typeId="30bd-8385-2b51-e039">6</characteristic>
            <characteristic name="H" typeId="a41f-60f6-2336-73ab">10</characteristic>
            <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">4</characteristic>
            <characteristic name="A" typeId="6b2b-37c4-6774-748b">6</characteristic>
            <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">9</characteristic>
            <characteristic name="TSA" typeId="2532-2940-06ec-7a6e"/>
            <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Monstruo, Demonio, Caos, Nurgle, Hechicero</characteristic>
            <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705">10</characteristic>
          </characteristics>
        </profile>
      </profiles>
      <rules>
        <rule id="44b3-7b61-a6a6-d36f" name="Avance imparable" hidden="false">
          <description>La Gran Inmundicia ignora la restricci�n de no poder marchar si hay enemigos a 20cm o menos.</description>
        </rule>
      </rules>
      <infoLinks>
        <infoLink id="2866-43fb-872b-7d1d" name="Aura Demon�aca" hidden="false" targetId="6ee8-71c7-3d74-f8ff" type="rule"/>
        <infoLink id="ee2e-c51c-5044-e5f7" name="Terror" hidden="false" targetId="31ab-3ff3-e34f-baac" type="rule"/>
        <infoLink id="3b66-c5ee-ef32-baa7" name="Objetivo grande" hidden="false" targetId="9e28-dc38-0f21-77f6" type="rule"/>
        <infoLink id="cfe2-90b6-582d-0759" name="Demonio" hidden="false" targetId="3b16-1038-ec5b-845b" type="rule"/>
        <infoLink id="a88d-c6dc-de41-92a2" name="Marcas del Caos" hidden="false" targetId="e389-b085-6f21-2a58" type="rule"/>
        <infoLink id="ceb1-a3f5-43fb-fde2" name="Dios del Caos" hidden="false" targetId="1358-d734-5293-f4cf" type="rule"/>
        <infoLink id="89d7-545b-d5b5-a391" name="Inestabilidad Demon�aca" hidden="false" targetId="8c45-e9fd-1a51-f92c" type="rule"/>
        <infoLink id="1daf-b05a-c8cc-7c10" name="General demon�aco" hidden="false" targetId="fdbe-5f7a-4255-58c7" type="rule"/>
        <infoLink id="c0dc-2eb6-44c9-869c" name="Personajes y unidades" hidden="false" targetId="c927-071c-5329-89c9" type="rule"/>
      </infoLinks>
      <categoryLinks>
        <categoryLink id="434f-d081-47bd-6363" name="New CategoryLink" hidden="false" targetId="9769-7233-6405-675e" primary="true"/>
        <categoryLink id="e75d-9ff2-9257-99f0" name="New CategoryLink" hidden="false" targetId="c647-4209-4e6c-206a" primary="false"/>
        <categoryLink id="ae57-f9ad-1437-1c66" name="New CategoryLink" hidden="false" targetId="184a-30ec-bf7c-b603" primary="false"/>
      </categoryLinks>
      <selectionEntries>
        <selectionEntry id="ec02-bea9-e2b9-e06a" name="Objetos m�gicos" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="7287-2231-a555-52b9" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="5e3e-9643-efe6-2e04" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="349c-4e5d-2dda-11a9" name="Nube de moscas" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="roster" value="1.0" percentValue="false" shared="true" includeChildSelections="true" includeChildForces="false" id="1f76-808a-4eec-94ac" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="f45f-6c10-2fb1-7e28" type="min"/>
              </constraints>
              <profiles>
                <profile id="0ae5-d69e-eb48-0983" name="Nube de moscas" hidden="false" typeId="7e35-c20a-e9e9-6dad" typeName="Talism�n">
                  <characteristics>
                    <characteristic name="Protecci�n" typeId="9f41-c15e-1f5f-9d01">Toda unidad o miniatura enemiga, mientras est� en contacto peana con peana con una o m�s miniaturas con Nube de Moscas, tiene un penalizador de -1 a todas sus tiradas para impactar en combate cuerpo a cuerpo. Ten en cuenta que el penalizador es aunque no ataque a miniaturas con Nube de Moscas. Las miniaturas con Nube de moscas son inmunes a las Nubes de moscas enemigas (�est�n acostumbrados a las moscas!).</characteristic>
                  </characteristics>
                </profile>
              </profiles>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="b2dc-231c-a0f4-733b" name="Torrente de corrupci�n" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="roster" value="1.0" percentValue="false" shared="true" includeChildSelections="true" includeChildForces="false" id="28d3-01cb-55e6-86aa" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="ea01-8707-21f0-1629" type="min"/>
              </constraints>
              <profiles>
                <profile id="2d1b-dec6-c2a2-821c" name="Torrente de corrupci�n" hidden="false" typeId="7e35-c20a-e9e9-6dad" typeName="Talism�n">
                  <characteristics>
                    <characteristic name="Protecci�n" typeId="9f41-c15e-1f5f-9d01">Se considera un disparo (no puede lanzarse en combate cuerpo a cuerpo, por ejemplo); realiza un ataque de plantilla de aliento (no son Ataques Flam�geros) que hace impactos de F3 con -2 a la tirada de salvaci�n por armadura.</characteristic>
                  </characteristics>
                </profile>
              </profiles>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
        <selectionEntry id="6a30-e4e3-94aa-1004" name="Ocupa una opci�n de comandante, una de h�roe y una de unidad singular" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="5422-5845-34a8-6e3a" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="7990-be4d-1fc6-7a5a" type="min"/>
          </constraints>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
      </selectionEntries>
      <selectionEntryGroups>
        <selectionEntryGroup id="2ca7-1810-6717-1d07" name="Armas" hidden="false" collective="false" import="true" defaultSelectionEntryId="232c-6ef3-5432-4c34">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="0030-60c6-47f6-b521" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="801c-2fe7-749d-4b36" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="232c-6ef3-5432-4c34" name="Arma de mano" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="566e-a5e6-1e21-4c93" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="f07d-1f7c-a26b-cae5" type="min"/>
              </constraints>
              <infoLinks>
                <infoLink id="0564-e24a-d592-cf63" name="Arma de mano" hidden="false" targetId="4645-41a2-83c2-d8bc" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="a42b-eb99-eb88-dc8b" name="Marca del Caos" hidden="false" collective="false" import="true" defaultSelectionEntryId="15a9-d928-f2cd-67ef">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="5704-16ab-5f74-f0b9" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="9eed-e582-b6c5-610d" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="15a9-d928-f2cd-67ef" name="Marca de Nurgle" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="5d8a-f54a-65d2-2cc5" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="b7ab-5803-3c7d-63b4" type="min"/>
              </constraints>
              <rules>
                <rule id="9f78-c8ea-5452-0347" name="Marca de Nurgle" hidden="false">
                  <description>Sin efecto adicional.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="77ca-bcb5-9031-cf66" name="Nivel" hidden="false" collective="false" import="true" defaultSelectionEntryId="08d3-8dc1-0433-eef3">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="728f-5a74-7e81-fce3" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="e2ca-8f7f-de6f-1b9e" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="08d3-8dc1-0433-eef3" name="Nivel 4" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="c5e0-2ee3-bc77-5131" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="149f-8d07-a673-9f44" type="min"/>
              </constraints>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="74de-b8b2-e7e9-2a0c" name="Saber" hidden="false" collective="false" import="true" defaultSelectionEntryId="b147-40bd-4d53-8b2f">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="e6c1-3a29-0f69-832e" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="924c-147e-357c-2799" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="b147-40bd-4d53-8b2f" name="Saber de Nurgle" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="ded4-29a3-c72d-22b5" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="2114-130a-6abc-041b" type="min"/>
              </constraints>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
      </selectionEntryGroups>
      <costs>
        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="600.0"/>
      </costs>
    </selectionEntry>
    <selectionEntry id="18aa-ad3a-bba7-9d49" name="Guardi�n de los secretos (ocupa opci�n extra de h�roe y de singular)" hidden="false" collective="false" import="true" type="model">
      <profiles>
        <profile id="f77b-6281-7740-e726" name="Guardi�n de los secretos" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
          <characteristics>
            <characteristic name="M" typeId="2d56-9cad-9242-37bd">20</characteristic>
            <characteristic name="HA" typeId="c87b-b820-6a47-1354">9</characteristic>
            <characteristic name="HP" typeId="8ab7-c800-6644-f5ec">0</characteristic>
            <characteristic name="F" typeId="79c2-0368-3eed-76b4">6</characteristic>
            <characteristic name="R" typeId="30bd-8385-2b51-e039">6</characteristic>
            <characteristic name="H" typeId="a41f-60f6-2336-73ab">6</characteristic>
            <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">10</characteristic>
            <characteristic name="A" typeId="6b2b-37c4-6774-748b">6</characteristic>
            <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">9</characteristic>
            <characteristic name="TSA" typeId="2532-2940-06ec-7a6e"/>
            <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Monstruo, Demonio, Caos, Slaanesh, Hechicero</characteristic>
            <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705">6</characteristic>
          </characteristics>
        </profile>
      </profiles>
      <infoLinks>
        <infoLink id="9ede-5ea7-45eb-3217" name="Aura Demon�aca" hidden="false" targetId="6ee8-71c7-3d74-f8ff" type="rule"/>
        <infoLink id="6c6c-7270-a573-0a78" name="Terror" hidden="false" targetId="31ab-3ff3-e34f-baac" type="rule"/>
        <infoLink id="5fbf-fb98-4157-db59" name="Objetivo grande" hidden="false" targetId="9e28-dc38-0f21-77f6" type="rule"/>
        <infoLink id="e90a-f9f8-5bd6-83f4" name="Demonio" hidden="false" targetId="3b16-1038-ec5b-845b" type="rule"/>
        <infoLink id="94ba-ae9e-e3a2-6d27" name="Dios del Caos" hidden="false" targetId="1358-d734-5293-f4cf" type="rule"/>
        <infoLink id="199c-2883-37df-386f" name="General demon�aco" hidden="false" targetId="fdbe-5f7a-4255-58c7" type="rule"/>
        <infoLink id="f15d-3dbb-2373-8ce0" name="Inestabilidad Demon�aca" hidden="false" targetId="8c45-e9fd-1a51-f92c" type="rule"/>
        <infoLink id="6d41-c636-0b81-0184" name="Marcas del Caos" hidden="false" targetId="e389-b085-6f21-2a58" type="rule"/>
        <infoLink id="366e-c893-c795-a2fa" name="Personajes y unidades" hidden="false" targetId="c927-071c-5329-89c9" type="rule"/>
      </infoLinks>
      <categoryLinks>
        <categoryLink id="d8cf-5831-cebf-0cb1" name="New CategoryLink" hidden="false" targetId="9769-7233-6405-675e" primary="true"/>
        <categoryLink id="8d37-7816-d806-c0fd" name="New CategoryLink" hidden="false" targetId="c647-4209-4e6c-206a" primary="false"/>
        <categoryLink id="19c9-a68e-582c-167f" name="New CategoryLink" hidden="false" targetId="184a-30ec-bf7c-b603" primary="false"/>
      </categoryLinks>
      <selectionEntries>
        <selectionEntry id="aa78-1bc5-5750-397e" name="Objetos m�gicos" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="c55b-006d-7073-ecd1" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="7ba8-5304-bff0-b474" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="26b4-208a-7e3b-33a7" name="Almizcle sopor�fero" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="roster" value="1.0" percentValue="false" shared="true" includeChildSelections="true" includeChildForces="false" id="0c6e-8b09-bec3-de2e" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="4f48-a31e-9905-bfe5" type="min"/>
              </constraints>
              <profiles>
                <profile id="6576-cc49-08ad-6bc4" name="Almizcle sopor�fero" hidden="false" typeId="7e35-c20a-e9e9-6dad" typeName="Talism�n">
                  <characteristics>
                    <characteristic name="Protecci�n" typeId="9f41-c15e-1f5f-9d01">Todas las unidades y personajes enemigos en contacto peana con peana con uno o m�s Demonios con Almizcle Sopor�fero ven su HA y su Iniciativa reducidas a la mitad (redondeando hacia arriba).</characteristic>
                  </characteristics>
                </profile>
              </profiles>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="c2bc-940c-4ae0-fbfa" name="Aura de Slaanesh" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="roster" value="1.0" percentValue="false" shared="true" includeChildSelections="true" includeChildForces="false" id="611a-0c9d-f6f9-13d1" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="d78e-baa9-aa07-b26a" type="min"/>
              </constraints>
              <profiles>
                <profile id="d57c-7d66-cb2e-46c6" name="Aura de Slaanesh" hidden="false" typeId="7e35-c20a-e9e9-6dad" typeName="Talism�n">
                  <characteristics>
                    <characteristic name="Protecci�n" typeId="9f41-c15e-1f5f-9d01">Todas las unidades y personajes enemigos en contacto peana con peana con uno o m�s Demonios con Aura de Slaanesh tienen un -1 a su Liderazgo, hasta un m�nimo de 2. </characteristic>
                  </characteristics>
                </profile>
              </profiles>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
        <selectionEntry id="3cbf-ee89-bcc5-4a9b" name="Ocupa una opci�n de comandante, una de h�roe y una de unidad singular" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="ff02-175a-1851-e636" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="1407-ef28-4b41-fc6f" type="min"/>
          </constraints>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
      </selectionEntries>
      <selectionEntryGroups>
        <selectionEntryGroup id="c956-77e7-d4c7-f6ce" name="Armas" hidden="false" collective="false" import="true" defaultSelectionEntryId="900f-3c3a-9938-c2fd">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="b766-ee6c-5bff-bf7c" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="7066-fe42-0560-4cfa" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="900f-3c3a-9938-c2fd" name="Arma de mano" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="f5f5-f883-c732-8050" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="5c02-47a6-c665-0bc7" type="min"/>
              </constraints>
              <infoLinks>
                <infoLink id="13ba-9b7f-bb55-064e" name="Arma de mano" hidden="false" targetId="4645-41a2-83c2-d8bc" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="dedd-7883-3e89-6dce" name="Marca del Caos" hidden="false" collective="false" import="true" defaultSelectionEntryId="ff85-ebc0-d4ff-f2c5">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="a531-722b-7ca2-3109" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="41a3-3a50-2d2e-771b" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="ff85-ebc0-d4ff-f2c5" name="Marca de Slaanesh" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="5494-efc5-d50f-0a3a" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="5145-b1f6-dcef-b3b0" type="min"/>
              </constraints>
              <rules>
                <rule id="7d58-6c83-c0e9-5677" name="Marca de Slaanesh" hidden="false">
                  <description>Sin efecto adicional.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="eec1-7af7-0d5c-3b21" name="Nivel" hidden="false" collective="false" import="true" defaultSelectionEntryId="10b1-1847-48c9-6dff">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="5aff-00a7-2bec-9476" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="634a-1cf6-90d6-aa23" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="10b1-1847-48c9-6dff" name="Nivel 4" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="3aab-c37f-cec4-c928" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="b706-ef16-4f57-400d" type="min"/>
              </constraints>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="b99c-48ee-4043-7721" name="Saber" hidden="false" collective="false" import="true" defaultSelectionEntryId="53d6-5c53-6f49-18a2">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="ab64-deaf-6241-7672" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="2703-e0a6-1ba3-dc78" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="53d6-5c53-6f49-18a2" name="Saber de Slaanesh" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="db3a-70f0-48c2-2080" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="7539-d111-25fb-3f74" type="min"/>
              </constraints>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
      </selectionEntryGroups>
      <costs>
        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="625.0"/>
      </costs>
    </selectionEntry>
    <selectionEntry id="05c5-359c-5dc8-c46b" name="Se�or de la transformaci�n (ocupa opci�n extra de h�roe y de singular)" hidden="false" collective="false" import="true" type="model">
      <profiles>
        <profile id="68c0-15a0-01f7-93f4" name="Se�or de la transformaci�n" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
          <characteristics>
            <characteristic name="M" typeId="2d56-9cad-9242-37bd">15</characteristic>
            <characteristic name="HA" typeId="c87b-b820-6a47-1354">6</characteristic>
            <characteristic name="HP" typeId="8ab7-c800-6644-f5ec">0</characteristic>
            <characteristic name="F" typeId="79c2-0368-3eed-76b4">6</characteristic>
            <characteristic name="R" typeId="30bd-8385-2b51-e039">6</characteristic>
            <characteristic name="H" typeId="a41f-60f6-2336-73ab">6</characteristic>
            <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">10</characteristic>
            <characteristic name="A" typeId="6b2b-37c4-6774-748b">5</characteristic>
            <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">9</characteristic>
            <characteristic name="TSA" typeId="2532-2940-06ec-7a6e"/>
            <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Monstruo, Demonio, Caos, Tzeentch, Hechicero.</characteristic>
            <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705">6</characteristic>
          </characteristics>
        </profile>
      </profiles>
      <infoLinks>
        <infoLink id="fd16-86d6-18ed-72eb" name="Aura Demon�aca" hidden="false" targetId="6ee8-71c7-3d74-f8ff" type="rule"/>
        <infoLink id="551a-8169-2f1a-278d" name="Terror" hidden="false" targetId="31ab-3ff3-e34f-baac" type="rule"/>
        <infoLink id="f757-e9be-e94d-07ed" name="Objetivo grande" hidden="false" targetId="9e28-dc38-0f21-77f6" type="rule"/>
        <infoLink id="0ec5-2a8f-bf28-ee26" name="Demonio" hidden="false" targetId="3b16-1038-ec5b-845b" type="rule"/>
        <infoLink id="3e5a-e2ad-9e04-d026" name="Dios del Caos" hidden="false" targetId="1358-d734-5293-f4cf" type="rule"/>
        <infoLink id="6a5d-2add-41d8-e2fa" name="General demon�aco" hidden="false" targetId="fdbe-5f7a-4255-58c7" type="rule"/>
        <infoLink id="4c22-5b52-400a-8464" name="Inestabilidad Demon�aca" hidden="false" targetId="8c45-e9fd-1a51-f92c" type="rule"/>
        <infoLink id="9adf-7bfd-5151-694d" name="Marcas del Caos" hidden="false" targetId="e389-b085-6f21-2a58" type="rule"/>
        <infoLink id="c0a3-d0f5-7089-50d1" name="Personajes y unidades" hidden="false" targetId="c927-071c-5329-89c9" type="rule"/>
        <infoLink id="ad47-4362-0e75-ca3a" name="Volar" hidden="false" targetId="90d6-fe4d-a823-314b" type="rule"/>
      </infoLinks>
      <categoryLinks>
        <categoryLink id="ccac-e99a-62a4-4c9b" name="New CategoryLink" hidden="false" targetId="9769-7233-6405-675e" primary="true"/>
        <categoryLink id="51f5-34ab-d997-c941" name="New CategoryLink" hidden="false" targetId="c647-4209-4e6c-206a" primary="false"/>
        <categoryLink id="812a-80d0-acf6-22b4" name="New CategoryLink" hidden="false" targetId="184a-30ec-bf7c-b603" primary="false"/>
      </categoryLinks>
      <selectionEntries>
        <selectionEntry id="ebba-078d-cd77-295c" name="Objetos m�gicos" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="6d1b-b758-bc2b-50a5" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="4b8a-dc77-a396-a4ad" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="17ee-130e-a58a-4c8a" name="Destruyehechizos" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="roster" value="1.0" percentValue="false" shared="true" includeChildSelections="true" includeChildForces="false" id="971f-d17e-b245-491c" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="3131-46a6-754f-17d4" type="min"/>
              </constraints>
              <profiles>
                <profile id="981d-f745-a604-646e" name="Destruyehechizos" hidden="false" typeId="7e35-c20a-e9e9-6dad" typeName="Talism�n">
                  <characteristics>
                    <characteristic name="Protecci�n" typeId="9f41-c15e-1f5f-9d01">Un s�lo uso. Act�a como un Pergamino de Dispersi�n a todos los efectos (p.e. no puede usarse contra un hechizo lanzado con Fuerza Irresistible). Adem�s, lanza 1D6: con 4+ el hechicero enemigo perder� el conocimiento de ese hechizo y no podr� lanzarlo m�s el resto de la batalla.</characteristic>
                  </characteristics>
                </profile>
              </profiles>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="c1be-cb25-da23-4054" name="Maestro de la hechicer�a" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="roster" value="1.0" percentValue="false" shared="true" includeChildSelections="true" includeChildForces="false" id="187c-4bf8-710d-2ab9" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="45be-0f44-3c25-15a9" type="min"/>
              </constraints>
              <profiles>
                <profile id="003d-6081-ad24-0a2c" name="Maestro de la hechicer�a" hidden="false" typeId="7e35-c20a-e9e9-6dad" typeName="Talism�n">
                  <characteristics>
                    <characteristic name="Protecci�n" typeId="9f41-c15e-1f5f-9d01">El Demonio sabe un hechizo m�s de los que le corresponden. Este hechizo debe ser del Saber de Tzeentch.</characteristic>
                  </characteristics>
                </profile>
              </profiles>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="5a4b-a304-e334-e52d" name="Voluntad de Tzeentch" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="roster" value="1.0" percentValue="false" shared="true" includeChildSelections="true" includeChildForces="false" id="9fc5-d297-5506-2f98" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="947f-703b-cd88-62cf" type="min"/>
              </constraints>
              <profiles>
                <profile id="f151-d44b-4c12-173a" name="Voluntad de Tzeentch" hidden="false" typeId="7e35-c20a-e9e9-6dad" typeName="Talism�n">
                  <characteristics>
                    <characteristic name="Protecci�n" typeId="9f41-c15e-1f5f-9d01">Una vez por turno, el Demonio puede repetir un dado de seis caras (1D6), incluyendo lanzando hechizo, dado de distancia de hu�da, etc. Una tirada repetida no se puede repetir.</characteristic>
                  </characteristics>
                </profile>
              </profiles>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
        <selectionEntry id="2b24-c2cf-3cc6-01a7" name="Ocupa una opci�n de comandante, una de h�roe y una de unidad singular" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="a35f-902d-a403-25a1" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="5778-9ded-cd06-e311" type="min"/>
          </constraints>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
      </selectionEntries>
      <selectionEntryGroups>
        <selectionEntryGroup id="6d13-5741-f1dd-2cbc" name="Armas" hidden="false" collective="false" import="true" defaultSelectionEntryId="70c1-6d86-b861-215e">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="b4a2-9d7d-1e96-2fa5" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="84d5-2c40-4c59-7169" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="70c1-6d86-b861-215e" name="Arma de mano" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="10c4-6df7-bf79-3e10" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="d5d3-b35f-ce40-c2bf" type="min"/>
              </constraints>
              <infoLinks>
                <infoLink id="0fc0-18b3-1a17-4f1d" name="Arma de mano" hidden="false" targetId="4645-41a2-83c2-d8bc" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="8bc1-1ecf-03ab-6acc" name="Marca del Caos" hidden="false" collective="false" import="true" defaultSelectionEntryId="c7eb-d086-f09b-6330">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="890e-550a-fb84-6e78" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="f853-3b81-1883-4a25" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="c7eb-d086-f09b-6330" name="Marca de Tzeentch" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="4ce5-8569-aaf1-f19c" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="079a-aada-40de-f30e" type="min"/>
              </constraints>
              <rules>
                <rule id="2514-34fc-de95-970b" name="Marca de Tzeentch" hidden="false">
                  <description>Sin efecto adicional.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="3ba2-98cb-c570-13ca" name="Nivel" hidden="false" collective="false" import="true" defaultSelectionEntryId="2725-a11f-e48e-7096">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="14c3-3268-c67a-014c" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="8f62-3be8-c516-91f7" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="2725-a11f-e48e-7096" name="Nivel 4" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="cf35-94b0-5985-6405" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="1bbc-7f59-ee99-8ca1" type="min"/>
              </constraints>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="2cad-e2d7-53aa-97da" name="Saber" hidden="false" collective="false" import="true" defaultSelectionEntryId="eb04-9ba1-7c1a-9ebd">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="2167-e784-4de5-5e4d" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="b6ba-3db5-edba-49e2" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="eb04-9ba1-7c1a-9ebd" name="Saber de Tzeentch" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="6dc2-ad17-db21-5c9f" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="3c31-a50b-7502-320f" type="min"/>
              </constraints>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
      </selectionEntryGroups>
      <costs>
        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="665.0"/>
      </costs>
    </selectionEntry>
    <selectionEntry id="12f4-9104-6fbe-b80c" name="Pr�ncipe demonio (ocupa una opci�n extra de h�roe)" hidden="false" collective="false" import="true" type="model">
      <profiles>
        <profile id="782c-fd48-f237-7834" name="Pr�ncipe demonio" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
          <characteristics>
            <characteristic name="M" typeId="2d56-9cad-9242-37bd">15</characteristic>
            <characteristic name="HA" typeId="c87b-b820-6a47-1354">8</characteristic>
            <characteristic name="HP" typeId="8ab7-c800-6644-f5ec">0</characteristic>
            <characteristic name="F" typeId="79c2-0368-3eed-76b4">5</characteristic>
            <characteristic name="R" typeId="30bd-8385-2b51-e039">5</characteristic>
            <characteristic name="H" typeId="a41f-60f6-2336-73ab">4</characteristic>
            <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">8</characteristic>
            <characteristic name="A" typeId="6b2b-37c4-6774-748b">5</characteristic>
            <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">9</characteristic>
            <characteristic name="TSA" typeId="2532-2940-06ec-7a6e"/>
            <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Infanter�a monstruosa, Demonio, Caos.</characteristic>
            <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705">3</characteristic>
          </characteristics>
        </profile>
      </profiles>
      <infoLinks>
        <infoLink id="b158-b528-a8ea-b06e" name="Aura Demon�aca" hidden="false" targetId="6ee8-71c7-3d74-f8ff" type="rule"/>
        <infoLink id="4ff4-66af-0ae5-3a8a" name="Terror" hidden="false" targetId="31ab-3ff3-e34f-baac" type="rule"/>
        <infoLink id="667a-82ee-dc40-d456" name="Demonio" hidden="false" targetId="3b16-1038-ec5b-845b" type="rule"/>
        <infoLink id="6814-d628-1f2f-612d" name="Dios del Caos" hidden="false" targetId="1358-d734-5293-f4cf" type="rule"/>
        <infoLink id="1fa7-638e-b123-c9f4" name="General demon�aco" hidden="false" targetId="fdbe-5f7a-4255-58c7" type="rule"/>
        <infoLink id="b1c6-1147-abde-473e" name="Inestabilidad Demon�aca" hidden="false" targetId="8c45-e9fd-1a51-f92c" type="rule"/>
        <infoLink id="d80b-8989-d37a-1405" name="Marcas del Caos" hidden="false" targetId="e389-b085-6f21-2a58" type="rule"/>
        <infoLink id="3e58-6e7d-c063-797d" name="Personajes y unidades" hidden="false" targetId="c927-071c-5329-89c9" type="rule"/>
      </infoLinks>
      <categoryLinks>
        <categoryLink id="6342-075e-7f24-8eed" name="New CategoryLink" hidden="false" targetId="9769-7233-6405-675e" primary="true"/>
        <categoryLink id="86ef-f72c-565b-e6fb" name="New CategoryLink" hidden="false" targetId="c647-4209-4e6c-206a" primary="false"/>
      </categoryLinks>
      <selectionEntries>
        <selectionEntry id="f719-4f75-9d08-36da" name="Objetos m�gicos (requieren marca apropiada)" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="7e31-85d9-b713-0fca" type="max"/>
          </constraints>
          <selectionEntryGroups>
            <selectionEntryGroup id="7697-f77b-abe2-4fef" name="Objetos m�gicos" hidden="false" collective="false" import="true">
              <constraints>
                <constraint field="53ea-00f4-9046-81ff" scope="parent" value="100.0" percentValue="false" shared="false" includeChildSelections="true" includeChildForces="false" id="445a-dcbd-70cb-89e4" type="max"/>
              </constraints>
              <entryLinks>
                <entryLink id="f788-dfc5-1816-59df" name="Recompensas demon�acas (Todos los Demonios)" hidden="false" collective="false" import="true" targetId="09e5-2a78-d818-f43d" type="selectionEntryGroup"/>
                <entryLink id="01c7-1b7e-1aa7-48b6" name="Recompensas demon�acas Khorne" hidden="false" collective="false" import="true" targetId="9545-2c88-b746-ffa3" type="selectionEntryGroup"/>
                <entryLink id="1b27-ad68-f730-5079" name="Recompensas demon�acas Nurgle" hidden="false" collective="false" import="true" targetId="5217-dada-4ff7-5204" type="selectionEntryGroup"/>
                <entryLink id="3f08-6ccb-4b94-7000" name="Recompensas demon�acas Slaanesh" hidden="false" collective="false" import="true" targetId="a8cf-90b4-f37b-6754" type="selectionEntryGroup"/>
                <entryLink id="999f-dc0b-54e8-9afc" name="Recompensas demon�acas Tzeentch" hidden="false" collective="false" import="true" targetId="bb87-d973-60f1-8db5" type="selectionEntryGroup"/>
              </entryLinks>
            </selectionEntryGroup>
          </selectionEntryGroups>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
        <selectionEntry id="0cf7-3f1c-b591-1f08" name="Ocupa una opci�n de comandante y una de h�roe" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="cf76-8aca-60c4-b44a" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="726e-dde7-4c1c-8d40" type="min"/>
          </constraints>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
        <selectionEntry id="332f-8d86-d4ac-0649" name="Volar" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="e091-caef-b9bd-05de" type="max"/>
          </constraints>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="45.0"/>
          </costs>
        </selectionEntry>
      </selectionEntries>
      <selectionEntryGroups>
        <selectionEntryGroup id="58a5-3a8c-de19-aafb" name="Armas" hidden="false" collective="false" import="true" defaultSelectionEntryId="d305-2848-b99e-b5dd">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="e1ce-c996-2de6-cc15" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="8eed-e278-aca6-c631" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="d305-2848-b99e-b5dd" name="Arma de mano" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="34cc-dea2-8a29-f2d8" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="397c-766b-06c4-5784" type="min"/>
              </constraints>
              <infoLinks>
                <infoLink id="9701-a89c-09b0-cf45" name="Arma de mano" hidden="false" targetId="4645-41a2-83c2-d8bc" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="3389-7f74-32c5-ee6c" name="Marca del Caos" hidden="false" collective="false" import="true" defaultSelectionEntryId="98c4-2f5b-bece-587e">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="8aff-7b74-6bf0-0c01" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="951f-15fc-fb1f-d5bf" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="ffc9-95c7-d10d-80eb" name="Marca de Tzeentch" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="7cac-f407-3713-33ed" type="max"/>
              </constraints>
              <rules>
                <rule id="6e0e-51eb-30cb-b4d1" name="Marca de Tzeentch" hidden="false">
                  <description>El Pr�ncipe Demonio pasa a ser un hechicero de nivel 4 que debe usar el saber de Tzeentch. Gana el tipo de unidad Tzeentch y el tipo de unidad Hechicero.</description>
                </rule>
              </rules>
              <selectionEntryGroups>
                <selectionEntryGroup id="8fe0-b7c6-cf4f-bc44" name="Nivel" hidden="false" collective="false" import="true">
                  <constraints>
                    <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="67ca-efa1-5b8d-f3b9" type="max"/>
                    <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="9b65-ce92-017e-d3fe" type="min"/>
                  </constraints>
                  <selectionEntries>
                    <selectionEntry id="86ef-1926-77aa-8885" name="Nivel 4" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="0390-f1ec-c308-2680" type="max"/>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="a1e5-e390-880a-eea9" type="min"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
                      </costs>
                    </selectionEntry>
                  </selectionEntries>
                </selectionEntryGroup>
                <selectionEntryGroup id="4f92-b4b3-8368-b8bd" name="Saber" hidden="false" collective="false" import="true">
                  <constraints>
                    <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="7beb-48cd-8a11-d928" type="max"/>
                    <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="1bc2-80e4-63e0-d7ef" type="min"/>
                  </constraints>
                  <selectionEntries>
                    <selectionEntry id="1ea8-dfb9-a238-bc02" name="Saber de Tzeentch" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="eaeb-5093-3787-d40e" type="max"/>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="a96c-e50d-9ff6-1dc6" type="min"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
                      </costs>
                    </selectionEntry>
                  </selectionEntries>
                </selectionEntryGroup>
              </selectionEntryGroups>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="150.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="a1d5-5efb-43dd-52cb" name="Marca de Khorne" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="a9ec-7e33-dac5-570b" type="max"/>
              </constraints>
              <rules>
                <rule id="f365-08be-c76c-2be8" name="Marca de Khorne" hidden="false">
                  <description>Gana el tipo de unidad Khorne. El Pr�ncipe Demonio est� sujeto a Furia Asesina (pese a ser inmune a psicolog�a). Mientras siga vivo, el ej�rcito tiene +1 dado de dispersi�n.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="35.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="0193-7d35-0b6a-8dde" name="Marca de Nurgle" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="a6fd-14c9-c128-2c37" type="max"/>
              </constraints>
              <rules>
                <rule id="f195-d352-4dd2-ab85" name="Marca de Nurgle" hidden="false">
                  <description>Gana el tipo de unidad Nurgle. El Pr�ncipe Demonio tiene H+1. Puede ser hechicero de nivel 1 a 4, a coste de 40 puntos por nivel (p.e. nivel 2 ser�an +80 puntos). En caso de darle alg�n nivel, gana el tipo Hechicero. Si es hechicero, debe usar el Saber de Nurgle.</description>
                </rule>
              </rules>
              <selectionEntryGroups>
                <selectionEntryGroup id="6e16-a968-5090-d0a3" name="Saber (si es hechicero)" hidden="false" collective="false" import="true">
                  <constraints>
                    <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="2772-4df7-e91d-c31a" type="max"/>
                  </constraints>
                  <selectionEntries>
                    <selectionEntry id="f12f-4383-4bc3-06f3" name="Saber de Nurgle" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="8a8d-301e-d4bb-dfe0" type="max"/>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="d77d-2010-5602-464c" type="min"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
                      </costs>
                    </selectionEntry>
                  </selectionEntries>
                </selectionEntryGroup>
                <selectionEntryGroup id="1b03-b853-32ac-7a50" name="Nivel" hidden="false" collective="false" import="true">
                  <constraints>
                    <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="d00f-aa30-d661-dd8d" type="max"/>
                    <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="68f4-a9ea-203b-e341" type="min"/>
                  </constraints>
                  <selectionEntries>
                    <selectionEntry id="0e47-aa89-ab9b-2a00" name="Nivel 0" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="0ad1-7e1a-4fd5-ccbc" type="max"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
                      </costs>
                    </selectionEntry>
                    <selectionEntry id="3ed0-26c8-5f46-851e" name="Nivel 3" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="0080-f80f-d7d8-b83d" type="max"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="120.0"/>
                      </costs>
                    </selectionEntry>
                    <selectionEntry id="b589-1a69-e7d8-1c42" name="Nivel 1" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="2050-7522-8369-7a8a" type="max"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="40.0"/>
                      </costs>
                    </selectionEntry>
                    <selectionEntry id="77ff-742e-be47-918a" name="Nivel 2" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="8216-78ce-bbb1-3563" type="max"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="80.0"/>
                      </costs>
                    </selectionEntry>
                    <selectionEntry id="d369-0dd8-2933-395d" name="Nivel 4" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="5bf3-a213-d122-1f9e" type="max"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="160.0"/>
                      </costs>
                    </selectionEntry>
                  </selectionEntries>
                </selectionEntryGroup>
              </selectionEntryGroups>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="50.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="604d-a618-24d2-0439" name="Marca de Slaanesh" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="eb94-6e52-0592-3489" type="max"/>
              </constraints>
              <rules>
                <rule id="b13c-3ec6-3c23-a8c9" name="Marca de Slaanesh" hidden="false">
                  <description>Gana el tipo de unidad Slaanesh. El Pr�ncipe Demonio siempre ataca primero. Si una miniatura enemiga en contacto tambi�n tiene esta regla, atacan por Iniciativa. Si tienen adem�s la misma Iniciativa, resuelve tirando 1D6 quien ataca primero. Puede ser hechicero de nivel 1 a 4, a coste de 40 puntos por nivel (p.e. nivel 2 ser�an +80 puntos). En caso de darle alg�n nivel, gana el tipo Hechicero. Si es hechicero, debe usar el Saber de Slaanesh.</description>
                </rule>
              </rules>
              <selectionEntryGroups>
                <selectionEntryGroup id="d5ed-ebe2-3949-6b9d" name="Saber (si es hechicero)" hidden="false" collective="false" import="true">
                  <constraints>
                    <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="6d46-a3d3-fd14-6e68" type="max"/>
                  </constraints>
                  <selectionEntries>
                    <selectionEntry id="decb-c4dc-8667-69d6" name="Saber de Slaanesh" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="421c-4984-6ea4-0c91" type="max"/>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="f8aa-d8e9-672b-b642" type="min"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
                      </costs>
                    </selectionEntry>
                  </selectionEntries>
                </selectionEntryGroup>
                <selectionEntryGroup id="ed00-22ee-152d-6fe7" name="Nivel" hidden="false" collective="false" import="true">
                  <constraints>
                    <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="74b7-f30a-3d00-5b97" type="max"/>
                    <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="94f1-8bc1-9e58-d9bf" type="min"/>
                  </constraints>
                  <selectionEntries>
                    <selectionEntry id="89f9-06a3-2f69-88ed" name="Nivel 0" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="d3bc-e2cd-4379-bb70" type="max"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
                      </costs>
                    </selectionEntry>
                    <selectionEntry id="81e4-c548-6322-33d5" name="Nivel 3" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="16e4-fcea-4e3b-e2cb" type="max"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="120.0"/>
                      </costs>
                    </selectionEntry>
                    <selectionEntry id="97f3-4d10-7b15-f682" name="Nivel 1" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="7479-2a15-f0f0-0973" type="max"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="40.0"/>
                      </costs>
                    </selectionEntry>
                    <selectionEntry id="0104-256a-2df8-64b1" name="Nivel 2" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="ab5a-20f1-d0e8-9d0e" type="max"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="80.0"/>
                      </costs>
                    </selectionEntry>
                    <selectionEntry id="9e87-bebe-7cad-da82" name="Nivel 4" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="c981-c709-3696-a26f" type="max"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="160.0"/>
                      </costs>
                    </selectionEntry>
                  </selectionEntries>
                </selectionEntryGroup>
              </selectionEntryGroups>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="25.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="98c4-2f5b-bece-587e" name="Marca del Caos Absoluto" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="de4d-7676-d479-ea3d" type="max"/>
              </constraints>
              <rules>
                <rule id="7ac9-f66c-4bdf-586a" name="Marca del Caos Absoluto" hidden="false">
                  <description>Puede ser hechicero de nivel 1 a 4, a coste de 40 puntos por nivel (p.e. nivel 2 ser�an +80 puntos). En caso de darle alg�n nivel, gana el tipo Hechicero. Si es hechicero, puede elegir Saber de las Sombras, Muerte o Fuego</description>
                </rule>
              </rules>
              <selectionEntryGroups>
                <selectionEntryGroup id="31e3-13c5-7b02-69c6" name="Saber (si es hechicero)" hidden="false" collective="false" import="true">
                  <constraints>
                    <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="71c7-2400-0126-a6ac" type="max"/>
                  </constraints>
                  <selectionEntries>
                    <selectionEntry id="b628-0151-dcf5-6ee1" name="Saber de las Sombras" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="00e8-635f-4524-345e" type="max"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
                      </costs>
                    </selectionEntry>
                    <selectionEntry id="c8e6-bf58-bcf8-9224" name="Saber de la Muerte" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="d1e4-0b35-731d-8664" type="max"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
                      </costs>
                    </selectionEntry>
                    <selectionEntry id="ea15-d287-7a53-bed6" name="Saber del Fuego" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="49e7-854f-ca38-de07" type="max"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
                      </costs>
                    </selectionEntry>
                  </selectionEntries>
                </selectionEntryGroup>
                <selectionEntryGroup id="bc6f-5ccc-f814-6455" name="Nivel" hidden="false" collective="false" import="true" defaultSelectionEntryId="0df7-4901-4059-46cc">
                  <constraints>
                    <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="318b-15f1-1527-77fb" type="max"/>
                    <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="81b6-ae9d-4712-e8d3" type="min"/>
                  </constraints>
                  <selectionEntries>
                    <selectionEntry id="0df7-4901-4059-46cc" name="Nivel 0" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="4758-f90c-508f-c1b5" type="max"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
                      </costs>
                    </selectionEntry>
                    <selectionEntry id="c064-1190-fe1f-5e1e" name="Nivel 3" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="235c-3351-fc67-29ed" type="max"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="120.0"/>
                      </costs>
                    </selectionEntry>
                    <selectionEntry id="a098-f67e-695f-dc38" name="Nivel 1" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="34c0-38ac-f315-4b13" type="max"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="40.0"/>
                      </costs>
                    </selectionEntry>
                    <selectionEntry id="8e22-7d3d-50a5-7fc2" name="Nivel 2" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="95b0-1db8-28fa-d225" type="max"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="80.0"/>
                      </costs>
                    </selectionEntry>
                    <selectionEntry id="635f-61f3-74b0-3fb5" name="Nivel 4" hidden="false" collective="false" import="true" type="upgrade">
                      <constraints>
                        <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="114a-be9d-d5ab-5522" type="max"/>
                      </constraints>
                      <costs>
                        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="160.0"/>
                      </costs>
                    </selectionEntry>
                  </selectionEntries>
                </selectionEntryGroup>
              </selectionEntryGroups>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
      </selectionEntryGroups>
      <costs>
        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="255.0"/>
      </costs>
    </selectionEntry>
    <selectionEntry id="cc8c-1283-8edc-2bdf" name="Minotauro de la condenaci�n" hidden="false" collective="false" import="true" type="model">
      <profiles>
        <profile id="39c9-91bd-573a-a2f6" name="Minotauro de la condenaci�n" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
          <characteristics>
            <characteristic name="M" typeId="2d56-9cad-9242-37bd">15</characteristic>
            <characteristic name="HA" typeId="c87b-b820-6a47-1354">6</characteristic>
            <characteristic name="HP" typeId="8ab7-c800-6644-f5ec">3</characteristic>
            <characteristic name="F" typeId="79c2-0368-3eed-76b4">5</characteristic>
            <characteristic name="R" typeId="30bd-8385-2b51-e039">5</characteristic>
            <characteristic name="H" typeId="a41f-60f6-2336-73ab">4</characteristic>
            <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">5</characteristic>
            <characteristic name="A" typeId="6b2b-37c4-6774-748b">5</characteristic>
            <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">9</characteristic>
            <characteristic name="TSA" typeId="2532-2940-06ec-7a6e"/>
            <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Infanter�a monstruosa, Caos, Minotauro, Bestia</characteristic>
            <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705">3</characteristic>
          </characteristics>
        </profile>
      </profiles>
      <infoLinks>
        <infoLink id="c47c-5033-64f8-9481" name="Miedo" hidden="false" targetId="42bd-162f-4bb2-c783" type="rule"/>
        <infoLink id="6f53-dcbc-c6b2-1367" name="Ansia de sangre" hidden="false" targetId="b16d-25c5-4691-7cc3" type="rule"/>
        <infoLink id="dfb2-d201-896d-f7e5" name="Dios del Caos" hidden="false" targetId="1358-d734-5293-f4cf" type="rule"/>
        <infoLink id="82c1-840a-b049-30ec" name="General demon�aco" hidden="false" targetId="fdbe-5f7a-4255-58c7" type="rule"/>
        <infoLink id="1dea-3fda-a7c3-7cee" name="Marcas del Caos" hidden="false" targetId="e389-b085-6f21-2a58" type="rule"/>
        <infoLink id="e31d-cf4c-76f5-a2b2" name="Personajes y unidades" hidden="false" targetId="c927-071c-5329-89c9" type="rule"/>
      </infoLinks>
      <categoryLinks>
        <categoryLink id="315f-e542-66ed-d202" name="New CategoryLink" hidden="false" targetId="9769-7233-6405-675e" primary="true"/>
      </categoryLinks>
      <selectionEntries>
        <selectionEntry id="afb4-a74c-6870-1135" name="Objetos m�gicos" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="0a57-081e-fbe6-1fde" type="max"/>
          </constraints>
          <selectionEntryGroups>
            <selectionEntryGroup id="9bea-044d-6bcf-dc18" name="Objetos m�gicos" hidden="false" collective="false" import="true">
              <constraints>
                <constraint field="53ea-00f4-9046-81ff" scope="parent" value="100.0" percentValue="false" shared="false" includeChildSelections="true" includeChildForces="false" id="fcbb-e6b9-808b-601c" type="max"/>
              </constraints>
              <entryLinks>
                <entryLink id="4d3a-7de5-8238-dc44" name="Armas m�gicas" hidden="false" collective="false" import="true" targetId="d8a6-c3b7-78cc-2abf" type="selectionEntryGroup"/>
              </entryLinks>
            </selectionEntryGroup>
          </selectionEntryGroups>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
      </selectionEntries>
      <selectionEntryGroups>
        <selectionEntryGroup id="04c6-fe33-03b9-cf8b" name="Armas" hidden="false" collective="false" import="true" defaultSelectionEntryId="801d-f3b5-634b-4882">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="bf0e-2fc2-0668-196c" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="871f-60e1-1119-649f" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="4352-70fa-b506-4e6d" name="Arma a dos manos" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="67d8-9267-202a-2a92" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="e9f5-2dcb-0cfe-5445" name="Arma a dos manos " hidden="false" targetId="bc8b-5380-77a9-7fe7" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="8.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="7b24-9582-f366-2204" name="Arma de mano adicional" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="74bf-0de8-8457-0f87" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="21d4-95d2-71a0-d036" name="Arma de mano adicional " hidden="false" targetId="ea69-c00a-f73d-2263" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="6.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="801d-f3b5-634b-4882" name="Arma de mano" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="5ada-de17-ecec-f61f" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="34de-cb1f-d48c-ea95" name="Arma de mano" hidden="false" targetId="4645-41a2-83c2-d8bc" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="b260-99b2-1bb6-00fd" name="Escudo" hidden="false" collective="false" import="true">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="a9ff-10de-defa-8353" type="max"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="3e43-365c-41d6-a632" name="Escudo" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="18ed-f55c-8a46-7e75" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="46ed-1968-28c7-c47a" name="Escudo" hidden="false" targetId="1e84-3cd7-87ca-0372" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="3.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="29f7-8089-652f-87c8" name="Marca del Caos" hidden="false" collective="false" import="true" defaultSelectionEntryId="0ad5-601d-aa4d-6d6b">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="52f2-c1fe-8f52-14c7" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="e9c5-a64f-0160-b08a" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="0ad5-601d-aa4d-6d6b" name="Marca del Caos absoluto" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="6c13-cd8c-be25-71e1" type="max"/>
              </constraints>
              <rules>
                <rule id="d1e9-5e6c-2941-5a45" name="Marca del Caos absoluto" hidden="false">
                  <description>El Minotauro de la Condenaci�n puede repetir cualquier chequeo de psicolog�a fallado. </description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="bb08-e59c-686f-6a71" name="Marca de Khorne" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="0031-5b04-f31a-9517" type="max"/>
              </constraints>
              <rules>
                <rule id="75e1-c8ef-cbe2-c125" name="Marca de Khorne" hidden="false">
                  <description>El Minotauro de la Condenaci�n est� sujeto a Furia Asesina. Mientras siga vivo, el ej�rcito tiene +1 dado de dispersi�n. Gana el tipo de unidad Khorne.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="40.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="60a7-91d4-7832-7953" name="Marca de Nurgle" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="6ccb-5543-4de6-6bbc" type="max"/>
              </constraints>
              <rules>
                <rule id="f662-c947-085a-e6e9" name="Marca de Nurgle" hidden="false">
                  <description>El Minotauro de la Condenaci�n tiene H+1. Gana el tipo de unidad Nurgle.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="50.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="9b29-545d-10fc-33b9" name="Marca de Tzeentch" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="126b-683d-14b5-27f7" type="max"/>
              </constraints>
              <rules>
                <rule id="1ca3-0a71-ebc1-38aa" name="Marca de Tzeentch" hidden="false">
                  <description>El Minotauro de la Condenaci�n pasa a ser un hechicero de nivel 2 que debe usar el saber de Tzeentch. Puede lanzar hechizos pese a llevar armadura y/o escudo (normal, no puede elegir armaduras m�gicas). Gana el tipo de unidad Tzeentch y el tipo de unidad Hechicero</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="80.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="734c-7a93-a679-5558" name="Marca de Slaanesh" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="1ca2-018c-b470-db01" type="max"/>
              </constraints>
              <rules>
                <rule id="7ea5-0fc3-9d04-667f" name="Marca de Slaanesh" hidden="false">
                  <description>El Minotauro de la Condenaci�n es inmune a psicolog�a. Gana el tipo de unidad Slaanesh.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="25.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="4b3a-73b0-fec7-6ee7" name="Armadura" hidden="false" collective="false" import="true">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="a447-8d4d-76ca-9112" type="max"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="1592-877b-6f94-d2c0" name="Armadura ligera" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="a1aa-4503-81fe-dd2e" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="bb48-6d7b-3667-0952" name="Armadura ligera" hidden="false" targetId="c534-e31e-c936-c2f2" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="3.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="abc4-dd64-5315-db61" name="Armadura pesada" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="5d6d-4e99-1317-43be" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="7c89-e09b-4873-39a3" name="Armadura pesada" hidden="false" targetId="dfbb-a75f-240a-704f" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="6.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
      </selectionEntryGroups>
      <costs>
        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="180.0"/>
      </costs>
    </selectionEntry>
    <selectionEntry id="4f0a-e635-8a22-5bc1" name="Gran cham�n del reba�o" hidden="false" collective="false" import="true" type="model">
      <profiles>
        <profile id="e0a3-14d0-b3e8-8ce5" name="Gran cham�n del reba�o" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
          <characteristics>
            <characteristic name="M" typeId="2d56-9cad-9242-37bd">12</characteristic>
            <characteristic name="HA" typeId="c87b-b820-6a47-1354">5</characteristic>
            <characteristic name="HP" typeId="8ab7-c800-6644-f5ec">3</characteristic>
            <characteristic name="F" typeId="79c2-0368-3eed-76b4">4</characteristic>
            <characteristic name="R" typeId="30bd-8385-2b51-e039">4</characteristic>
            <characteristic name="H" typeId="a41f-60f6-2336-73ab">3</characteristic>
            <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">5</characteristic>
            <characteristic name="A" typeId="6b2b-37c4-6774-748b">2</characteristic>
            <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">7</characteristic>
            <characteristic name="TSA" typeId="2532-2940-06ec-7a6e"/>
            <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Infanter�a, Caos, Bestia, Hechicero</characteristic>
            <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705">1</characteristic>
          </characteristics>
        </profile>
      </profiles>
      <infoLinks>
        <infoLink id="425d-94d4-9017-9aef" name="Dios del Caos" hidden="false" targetId="1358-d734-5293-f4cf" type="rule"/>
        <infoLink id="a923-16de-fbc8-0512" name="Emboscada" hidden="false" targetId="22d6-8641-8f0b-3f3b" type="rule"/>
        <infoLink id="6927-b28b-0188-cfd0" name="General demon�aco" hidden="false" targetId="fdbe-5f7a-4255-58c7" type="rule"/>
        <infoLink id="d441-0eaa-a6c8-e981" name="Marcas del Caos" hidden="false" targetId="e389-b085-6f21-2a58" type="rule"/>
        <infoLink id="41c9-ea83-b247-1e24" name="Personajes y unidades" hidden="false" targetId="c927-071c-5329-89c9" type="rule"/>
        <infoLink id="576d-3a9b-ceee-ac3a" name="Saberes de magia" hidden="false" targetId="6abc-f660-b4ae-0699" type="rule"/>
      </infoLinks>
      <categoryLinks>
        <categoryLink id="960d-7332-bbd0-abad" name="New CategoryLink" hidden="false" targetId="9769-7233-6405-675e" primary="true"/>
      </categoryLinks>
      <selectionEntries>
        <selectionEntry id="3439-7df4-e932-1a98" name="Objetos m�gicos" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="23c6-093d-f836-473b" type="max"/>
          </constraints>
          <selectionEntryGroups>
            <selectionEntryGroup id="68f0-141a-28af-b21c" name="Objetos m�gicos" hidden="false" collective="false" import="true">
              <constraints>
                <constraint field="53ea-00f4-9046-81ff" scope="parent" value="100.0" percentValue="false" shared="false" includeChildSelections="true" includeChildForces="false" id="82bd-ad0d-43fb-6bef" type="max"/>
              </constraints>
              <selectionEntries>
                <selectionEntry id="4e90-9aae-2cbd-7cf5" name="Armadura del Caos" hidden="false" collective="false" import="true" type="upgrade">
                  <constraints>
                    <constraint field="selections" scope="roster" value="1.0" percentValue="false" shared="true" includeChildSelections="true" includeChildForces="false" id="daf1-1e20-20d4-cd88" type="max"/>
                  </constraints>
                  <profiles>
                    <profile id="af7b-7ea2-146b-7e4c" name="Armadura del Caos" hidden="false" typeId="7895-caab-ea85-11a6" typeName="Armadura">
                      <characteristics>
                        <characteristic name="Salvaci�n por armadura" typeId="b9eb-92d5-e891-ed20">4+</characteristic>
                        <characteristic name="Reglas especiales" typeId="9bf4-3410-57d2-8871">Cualquier personaje puede elegir esta Armadura del Caos, incluso Chamanes y Grandes Chamanes. La miniatura gana una tirada de salvaci�n por armadura de 4+ que puede mejorarse con otro equipo (salvo armaduras ligeras o pesadas). Los personajes con esta armadura pueden lanzar magia de la forma habitual.</characteristic>
                      </characteristics>
                    </profile>
                  </profiles>
                  <costs>
                    <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="10.0"/>
                  </costs>
                </selectionEntry>
              </selectionEntries>
              <entryLinks>
                <entryLink id="8613-74b3-7e96-796b" name="Armas m�gicas" hidden="false" collective="false" import="true" targetId="d8a6-c3b7-78cc-2abf" type="selectionEntryGroup"/>
                <entryLink id="b141-4a65-8e3c-0c65" name="Mutaciones del caos" hidden="false" collective="false" import="true" targetId="c689-34ee-ec75-6d55" type="selectionEntryGroup"/>
                <entryLink id="e69b-1c95-f3ab-8f91" name="Objetos arcanos, requiere ser hechicero" hidden="false" collective="false" import="true" targetId="156e-b4bc-9c95-dc82" type="selectionEntryGroup"/>
                <entryLink id="13da-3372-6f61-b927" name="Talismanes" hidden="false" collective="false" import="true" targetId="41e0-e1dd-c0b1-8fce" type="selectionEntryGroup"/>
              </entryLinks>
            </selectionEntryGroup>
          </selectionEntryGroups>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
      </selectionEntries>
      <selectionEntryGroups>
        <selectionEntryGroup id="417b-4e63-be04-4412" name="Nivel" hidden="false" collective="false" import="true" defaultSelectionEntryId="6a49-91ad-fe4f-82f1">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="0e52-68d9-d647-330d" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="d182-9e7c-a7bf-aac4" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="6a49-91ad-fe4f-82f1" name="Nivel 3" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="1e1c-234d-ca65-0bce" type="max"/>
              </constraints>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="ed2c-3656-c080-0a61" name="Nivel 4" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="6eac-b6e4-4fb0-97c0" type="max"/>
              </constraints>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="35.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="7860-2152-afb4-dd86" name="Saber" hidden="false" collective="false" import="true">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="ab77-6d4c-ea0c-e068" type="max"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="0a7c-082a-8640-f1d7" name="Saber de las Sombras" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="3cd5-9425-fe97-869b" type="max"/>
              </constraints>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="52c1-7528-8069-22f8" name="Saber de la Muerte" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="247d-fa00-378f-a16b" type="max"/>
              </constraints>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="a771-b886-903f-274c" name="Saber de las Bestias" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="602e-ae7e-5b77-bf70" type="max"/>
              </constraints>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="f6c0-fe19-90c3-6e10" name="Saber de Nurgle (requiere Marca de Nurgle)" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="a011-e645-d25f-0718" type="max"/>
              </constraints>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="b96b-82c2-bf61-8917" name="Saber de Slaanesh (requiere Marca de Slaanesh)" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="7e7c-3022-380d-e738" type="max"/>
              </constraints>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="054b-4b1f-cc2a-3466" name="Armas" hidden="false" collective="false" import="true" defaultSelectionEntryId="262c-bf29-ada7-5311">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="b20a-b31b-b704-fd4c" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="9d58-ab3e-c258-4661" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="262c-bf29-ada7-5311" name="Arma de mano" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="4402-655b-e403-d339" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="819d-94e6-4be1-d97a" name="Arma de mano" hidden="false" targetId="4645-41a2-83c2-d8bc" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="a3ca-23e4-5518-96c6" name="Arma de mano adicional" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="6561-ea6b-6d1f-131c" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="d987-994a-1af0-4811" name="Arma de mano adicional " hidden="false" targetId="ea69-c00a-f73d-2263" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="6.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="9a43-5e1d-ef8e-34a0" name="Cayado de la manada" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="0ac1-9e58-8721-d22e" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="75ec-ba39-2ed5-9dd0" name="Cayado de la manada" hidden="false" targetId="c63b-cb27-cf35-7665" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="8.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="7a02-3e22-9d62-8e1f" name="Montura" hidden="false" collective="false" import="true">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="fc0f-a64e-15cb-7244" type="max"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="3a22-bcc0-659b-81f7" name="Carro de tuskgors (cuenta como unidad especial, sustituye al bestigor de la tripulaci�n)" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="a342-25fa-6fd6-44db" type="max"/>
              </constraints>
              <entryLinks>
                <entryLink id="f8d1-4c56-6480-5964" name="Carro de tuskgors" hidden="false" collective="false" import="true" targetId="e1c0-4cf5-e0dc-503a" type="selectionEntry"/>
              </entryLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="85.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="307b-0e97-c003-3d71" name="Marca del Caos" hidden="false" collective="false" import="true" defaultSelectionEntryId="f47a-d433-e060-289d">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="57ee-523c-a646-445d" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="cf5c-6fb3-e8fd-dc84" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="f47a-d433-e060-289d" name="Marca del Caos absoluto" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="68a6-c479-5e64-84be" type="max"/>
              </constraints>
              <rules>
                <rule id="8923-e3f7-3040-9b25" name="Marca del Caos absoluto" hidden="false">
                  <description>El Gran Cham�n del Reba�o puede repetir cualquier chequeo de psicolog�a fallado. Puede usar el Saber de las Bestias, Sombras o Muerte.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="3b96-a66b-6d40-3e8f" name="Marca de Nurgle" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="91c4-a5ad-e699-e6f0" type="max"/>
              </constraints>
              <rules>
                <rule id="ea05-a410-6689-be53" name="Marca de Nurgle" hidden="false">
                  <description>El Gran Cham�n del Reba�o tiene H+1 y causa Miedo. Debe usar el Saber de Nurgle. Gana el tipo de unidad Nurgle.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="50.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="7453-dbe6-9f9d-fe8f" name="Marca de Slaanesh" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="7a78-d076-1bfe-91a8" type="max"/>
              </constraints>
              <rules>
                <rule id="7b0d-ba4b-a225-965f" name="Marca de Slaanesh" hidden="false">
                  <description>El Gran Cham�n del Reba�o es inmune a psicolog�a. Debe usar el Saber de Slaanesh. Gana el tipo de unidad Slaanesh.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="25.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
      </selectionEntryGroups>
      <costs>
        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="180.0"/>
      </costs>
    </selectionEntry>
    <selectionEntry id="98cb-3234-8195-bbff" name="Caudillo hombre bestia" hidden="false" collective="false" import="true" type="model">
      <profiles>
        <profile id="5d59-2ae2-ccca-9f16" name="Caudillo hombre bestia" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
          <characteristics>
            <characteristic name="M" typeId="2d56-9cad-9242-37bd">12</characteristic>
            <characteristic name="HA" typeId="c87b-b820-6a47-1354">6</characteristic>
            <characteristic name="HP" typeId="8ab7-c800-6644-f5ec">3</characteristic>
            <characteristic name="F" typeId="79c2-0368-3eed-76b4">5</characteristic>
            <characteristic name="R" typeId="30bd-8385-2b51-e039">4</characteristic>
            <characteristic name="H" typeId="a41f-60f6-2336-73ab">3</characteristic>
            <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">6</characteristic>
            <characteristic name="A" typeId="6b2b-37c4-6774-748b">4</characteristic>
            <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">8</characteristic>
            <characteristic name="TSA" typeId="2532-2940-06ec-7a6e"/>
            <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Infanter�a, Caos, Bestia</characteristic>
            <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705">1</characteristic>
          </characteristics>
        </profile>
      </profiles>
      <rules>
        <rule id="5e56-f1e7-4102-f428" name="Objetos arcanos" hidden="false">
          <description>S�lo si es hechicero (por ejemplo gracias a la Marca de Tzeentch).</description>
        </rule>
        <rule id="5465-5900-52d9-1be2" name="Alfa de la manada" hidden="false">
          <description>Si tu general es un Caudillo Hombre Bestia, una �nica Manada de Bestias puede llevar un estandarte m�gico de hasta 25 puntos.</description>
        </rule>
      </rules>
      <infoLinks>
        <infoLink id="81ba-c951-1710-ba43" name="Dios del Caos" hidden="false" targetId="1358-d734-5293-f4cf" type="rule"/>
        <infoLink id="384e-f566-60a0-86f1" name="Emboscada" hidden="false" targetId="22d6-8641-8f0b-3f3b" type="rule"/>
        <infoLink id="809d-32d7-2f67-a0ea" name="General demon�aco" hidden="false" targetId="fdbe-5f7a-4255-58c7" type="rule"/>
        <infoLink id="c56d-6f46-8ffb-6167" name="Marcas del Caos" hidden="false" targetId="e389-b085-6f21-2a58" type="rule"/>
        <infoLink id="669f-f869-c25b-938f" name="Personajes y unidades" hidden="false" targetId="c927-071c-5329-89c9" type="rule"/>
      </infoLinks>
      <categoryLinks>
        <categoryLink id="95a6-4a0c-69ff-eb23" name="New CategoryLink" hidden="false" targetId="9769-7233-6405-675e" primary="true"/>
      </categoryLinks>
      <selectionEntries>
        <selectionEntry id="1e45-5621-792f-da7b" name="Objetos m�gicos" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="5822-e263-3134-a523" type="max"/>
          </constraints>
          <selectionEntryGroups>
            <selectionEntryGroup id="297f-5731-5745-63e5" name="Objetos m�gicos" hidden="false" collective="false" import="true">
              <constraints>
                <constraint field="53ea-00f4-9046-81ff" scope="parent" value="100.0" percentValue="false" shared="false" includeChildSelections="true" includeChildForces="false" id="fdcd-f0fe-6ea0-28d3" type="max"/>
              </constraints>
              <entryLinks>
                <entryLink id="57e0-abe8-7031-b2c7" name="Armas m�gicas" hidden="false" collective="false" import="true" targetId="d8a6-c3b7-78cc-2abf" type="selectionEntryGroup"/>
                <entryLink id="257c-d56a-b883-4f66" name="Armaduras m�gicas" hidden="false" collective="false" import="true" targetId="7808-5777-6461-8ee9" type="selectionEntryGroup"/>
                <entryLink id="d529-f514-330b-15b0" name="Objetos arcanos, requiere ser hechicero" hidden="false" collective="false" import="true" targetId="156e-b4bc-9c95-dc82" type="selectionEntryGroup"/>
                <entryLink id="fdf7-9959-af2f-79cf" name="Talismanes" hidden="false" collective="false" import="true" targetId="41e0-e1dd-c0b1-8fce" type="selectionEntryGroup"/>
                <entryLink id="f70f-927b-a519-10e1" name="Mutaciones del caos" hidden="false" collective="false" import="true" targetId="c689-34ee-ec75-6d55" type="selectionEntryGroup"/>
              </entryLinks>
            </selectionEntryGroup>
          </selectionEntryGroups>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
      </selectionEntries>
      <selectionEntryGroups>
        <selectionEntryGroup id="496d-b21b-efab-e9e6" name="Armas" hidden="false" collective="false" import="true" defaultSelectionEntryId="c4f7-7df3-1a5f-eda8">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="6471-543c-6afc-238e" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="5521-bc4e-54ec-dd8a" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="8b61-c941-6ce0-9410" name="Arma a dos manos" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="8756-2c08-61c4-a4dd" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="dea4-4722-375e-bb57" name="Arma a dos manos " hidden="false" targetId="bc8b-5380-77a9-7fe7" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="6.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="9ccb-31ff-16e1-3ce2" name="Arma de mano adicional" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="fea7-3219-f81e-5bfb" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="ce42-e467-c974-1010" name="Arma de mano adicional " hidden="false" targetId="ea69-c00a-f73d-2263" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="4.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="c4f7-7df3-1a5f-eda8" name="Arma de mano" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="ddef-1094-c85e-5eb5" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="24c0-db10-14e8-69d3" name="Arma de mano" hidden="false" targetId="4645-41a2-83c2-d8bc" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="7bcd-f897-bef8-7929" name="Montura" hidden="false" collective="false" import="true">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="f5e9-84e2-f021-12ed" type="max"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="8723-a666-cdd3-663a" name="Carro de tuskgors (cuenta como unidad especial, sustituye al bestigor de la tripulaci�n)" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="0bcc-3185-6842-e381" type="max"/>
              </constraints>
              <entryLinks>
                <entryLink id="72ca-6c3d-430a-c84e" name="Carro de tuskgors" hidden="false" collective="false" import="true" targetId="e1c0-4cf5-e0dc-503a" type="selectionEntry"/>
              </entryLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="85.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="6b98-3458-54da-cef6" name="Escudo" hidden="false" collective="false" import="true">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="78f7-a054-b4fc-d419" type="max"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="11e4-7faf-2c2a-c1dd" name="Escudo" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="5a95-a00c-0392-f3fc" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="7a09-d40f-0e02-5c0b" name="Escudo" hidden="false" targetId="1e84-3cd7-87ca-0372" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="3.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="1d80-ad3b-6d5d-434b" name="Marca del Caos" hidden="false" collective="false" import="true" defaultSelectionEntryId="7267-720c-639a-0686">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="0536-1586-bf2f-b2e2" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="9c1a-4631-7732-652a" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="7267-720c-639a-0686" name="Marca del Caos absoluto" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="c01c-2f96-de16-5aba" type="max"/>
              </constraints>
              <rules>
                <rule id="d3a2-be0d-92a8-38eb" name="Marca del Caos absoluto" hidden="false">
                  <description>El Caudillo puede repetir cualquier chequeo de psicolog�a fallado.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="f194-855b-2c9d-e4ae" name="Marca de Khorne" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="d034-2e7a-9688-01f0" type="max"/>
              </constraints>
              <rules>
                <rule id="9a6a-ce36-d60a-acaa" name="Marca de Khorne" hidden="false">
                  <description>El Caudillo est� sujeto a Furia Asesina (pero no su montura, aunque toda la miniatura estar� sujeta a los efectos de movimientos obligatorios). Mientras siga vivo, el ej�rcito tiene +1 dado de dispersi�n. Gana el tipo de unidad Khorne.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="40.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="8ec2-6206-4471-4ff4" name="Marca de Nurgle" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="9df9-3b76-ead1-eae3" type="max"/>
              </constraints>
              <rules>
                <rule id="556f-7d73-e101-00a3" name="Marca de Nurgle" hidden="false">
                  <description>El Caudillo tiene H+1 y causa Miedo. Gana el tipo de unidad Nurgle.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="50.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="4b71-f52e-935a-7ce5" name="Marca de Tzeentch" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="c96a-f908-f145-21dc" type="max"/>
              </constraints>
              <rules>
                <rule id="a126-90f9-7f13-6a95" name="Marca de Tzeentch" hidden="false">
                  <description>El Caudillo pasa a ser un hechicero de nivel 4 que debe usar el saber de Tzeentch. Puede lanzar hechizos pese a llevar armadura y/o escudo (normal o m�gica). Gana el tipo de unidad Tzeentch.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="140.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="baaa-9fa3-ae10-36f1" name="Marca de Slaanesh" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="ae00-97d6-5f34-a6a6" type="max"/>
              </constraints>
              <rules>
                <rule id="939c-29f5-0cad-92ab" name="Marca de Slaanesh" hidden="false">
                  <description>El Caudillo es inmune a psicolog�a. Gana el tipo de unidad Slaanesh.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="25.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="7dad-4de4-55cc-7036" name="Armadura" hidden="false" collective="false" import="true">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="d81b-d2d6-f525-b2c8" type="max"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="4340-c4f9-faf4-1b4c" name="Armadura ligera" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="99ee-3bd7-4b7c-ade1" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="656a-a15e-3b36-2e50" name="Armadura ligera" hidden="false" targetId="c534-e31e-c936-c2f2" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="3.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="6c9d-fb64-e6c5-30ea" name="Armadura pesada" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="a67a-de26-db9c-b2d4" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="2d67-3826-6de2-3dc4" name="Armadura pesada" hidden="false" targetId="dfbb-a75f-240a-704f" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="6.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
      </selectionEntryGroups>
      <costs>
        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="95.0"/>
      </costs>
    </selectionEntry>
    <selectionEntry id="3497-ac94-a6fd-9b3f" name="Se�or del Caos" hidden="false" collective="false" import="true" type="model">
      <profiles>
        <profile id="9c67-c413-4c34-e7fe" name="Se�or del Caos" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
          <characteristics>
            <characteristic name="M" typeId="2d56-9cad-9242-37bd">10</characteristic>
            <characteristic name="HA" typeId="c87b-b820-6a47-1354">8</characteristic>
            <characteristic name="HP" typeId="8ab7-c800-6644-f5ec">3</characteristic>
            <characteristic name="F" typeId="79c2-0368-3eed-76b4">5</characteristic>
            <characteristic name="R" typeId="30bd-8385-2b51-e039">5</characteristic>
            <characteristic name="H" typeId="a41f-60f6-2336-73ab">3</characteristic>
            <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">8</characteristic>
            <characteristic name="A" typeId="6b2b-37c4-6774-748b">5</characteristic>
            <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">9</characteristic>
            <characteristic name="TSA" typeId="2532-2940-06ec-7a6e">4+</characteristic>
            <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Infanter�a, Humano, Caos</characteristic>
            <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705">1</characteristic>
          </characteristics>
        </profile>
      </profiles>
      <rules>
        <rule id="8bb5-e685-5b4a-6efd" name="Objetos arcanos" hidden="false">
          <description>S�lo si es hechicero (por ejemplo gracias a la Marca de Tzeentch).</description>
        </rule>
      </rules>
      <infoLinks>
        <infoLink id="227c-3a22-a22a-fcb6" name="Dios del Caos" hidden="false" targetId="1358-d734-5293-f4cf" type="rule"/>
        <infoLink id="a0c0-3945-c532-a619" name="Marcas del Caos" hidden="false" targetId="e389-b085-6f21-2a58" type="rule"/>
        <infoLink id="0e45-dc5b-1375-df71" name="Personajes y unidades" hidden="false" targetId="c927-071c-5329-89c9" type="rule"/>
        <infoLink id="d9a1-bf6b-120f-67f6" name="General demon�aco" hidden="false" targetId="fdbe-5f7a-4255-58c7" type="rule"/>
      </infoLinks>
      <categoryLinks>
        <categoryLink id="0b67-d8cf-3dca-60cd" name="New CategoryLink" hidden="false" targetId="9769-7233-6405-675e" primary="true"/>
      </categoryLinks>
      <selectionEntries>
        <selectionEntry id="63e9-4148-fa7c-858a" name="Objetos m�gicos" hidden="false" collective="false" import="true" type="upgrade">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="75c9-84c8-74c0-4d30" type="max"/>
          </constraints>
          <selectionEntryGroups>
            <selectionEntryGroup id="38b3-61f0-1a3c-d153" name="Objetos m�gicos" hidden="false" collective="false" import="true">
              <constraints>
                <constraint field="53ea-00f4-9046-81ff" scope="parent" value="100.0" percentValue="false" shared="false" includeChildSelections="true" includeChildForces="false" id="c4dc-91ee-8fc3-cd9e" type="max"/>
              </constraints>
              <entryLinks>
                <entryLink id="bd27-9e1a-d899-38f0" name="Armas m�gicas" hidden="false" collective="false" import="true" targetId="d8a6-c3b7-78cc-2abf" type="selectionEntryGroup"/>
                <entryLink id="29d9-41f7-f025-c2b4" name="Armaduras m�gicas" hidden="false" collective="false" import="true" targetId="7808-5777-6461-8ee9" type="selectionEntryGroup"/>
                <entryLink id="240c-d9d4-f4c3-8753" name="Mutaciones del caos" hidden="false" collective="false" import="true" targetId="c689-34ee-ec75-6d55" type="selectionEntryGroup"/>
                <entryLink id="21ec-c62e-5054-3dc2" name="Objetos hechizados" hidden="false" collective="false" import="true" targetId="9824-2796-dc27-0f75" type="selectionEntryGroup"/>
                <entryLink id="1808-fc94-fede-e2c5" name="Objetos arcanos, requiere ser hechicero" hidden="false" collective="false" import="true" targetId="156e-b4bc-9c95-dc82" type="selectionEntryGroup"/>
                <entryLink id="14ab-9e42-369c-ec6c" name="Talismanes" hidden="false" collective="false" import="true" targetId="41e0-e1dd-c0b1-8fce" type="selectionEntryGroup"/>
              </entryLinks>
            </selectionEntryGroup>
          </selectionEntryGroups>
          <costs>
            <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
          </costs>
        </selectionEntry>
      </selectionEntries>
      <selectionEntryGroups>
        <selectionEntryGroup id="c18a-e527-a3b8-8e1f" name="Armadura" hidden="false" collective="false" import="true">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="1657-f838-1709-c352" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="ee73-d170-b66c-30fe" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="8caf-c965-4943-74a3" name="Armadura del Caos" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="fd00-301e-5063-eecf" type="max"/>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="c46e-96c9-f881-4796" type="min"/>
              </constraints>
              <infoLinks>
                <infoLink id="2e84-b4ab-356c-e0f3" name="Armadura del Caos" hidden="false" targetId="92fc-37fc-c654-b985" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="7caa-a945-1ceb-b634" name="Armas" hidden="false" collective="false" import="true" defaultSelectionEntryId="a15a-911c-ad81-5d93">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="31f2-7051-e6ee-1c6e" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="0cac-b868-5f05-cef2" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="0958-a4d7-7665-47c6" name="Arma a dos manos" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="1009-ecdf-7efc-b7f9" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="e8b4-0052-34a7-ea0d" name="Arma a dos manos " hidden="false" targetId="bc8b-5380-77a9-7fe7" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="6.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="7400-79c4-7af4-da20" name="Arma de mano adicional" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="4fd0-f343-d0ac-0850" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="586c-f253-38aa-2a02" name="Arma de mano adicional " hidden="false" targetId="ea69-c00a-f73d-2263" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="6.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="6c0c-dcb0-55d1-5aca" name="Mayal" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="75d2-efba-e806-bda4" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="c245-da16-bed8-5f98" name="Mayal" hidden="false" targetId="8d08-4e9d-35c7-8005" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="3.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="a15a-911c-ad81-5d93" name="Arma de mano" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="3c3d-235f-800d-d4e8" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="96b2-ddf6-6461-0888" name="Arma de mano" hidden="false" targetId="4645-41a2-83c2-d8bc" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="f831-fd3c-805e-b0c2" name="Lanza de caballer�a" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="6732-196a-7245-70dc" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="a48b-767c-7656-80e9" name="Lanza de caballer�a" hidden="false" targetId="5bcd-ff0b-d571-38d0" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="9.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="ccc3-a341-b67e-5363" name="Alabarda" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="c4ce-574c-8330-398b" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="264f-1995-9922-2782" name="Alabarda" hidden="false" targetId="ee3a-8a10-edff-cefe" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="6.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="f835-e37f-338e-dda3" name="Montura" hidden="false" collective="false" import="true">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="12d7-0c6d-1eea-1094" type="max"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="3da5-533e-c277-184a" name="Corcel del Caos con barda" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="775c-bac9-b037-28e2" type="max"/>
              </constraints>
              <entryLinks>
                <entryLink id="3bdd-2fc7-98a8-d265" name="Corcel del Caos con barda" hidden="false" collective="false" import="true" targetId="7877-b96e-5cbb-e65a" type="selectionEntry"/>
              </entryLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="24.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="3b41-fee8-f2d6-36d4" name="Montura demon�aca" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="c815-1414-8766-0c6a" type="max"/>
              </constraints>
              <entryLinks>
                <entryLink id="2dde-c5c1-af6a-9d1c" name="Montura Demon�aca" hidden="false" collective="false" import="true" targetId="c1ba-bf24-73c3-a668" type="selectionEntry"/>
              </entryLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="50.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="406a-ab95-2b59-c819" name="Diablo de Slaanesh (requiere Marca de Slaanesh)" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="5756-2bf2-3c7a-defb" type="max"/>
              </constraints>
              <entryLinks>
                <entryLink id="d2cc-2b5d-3916-9a78" name="Diablo de Slaanesh" hidden="false" collective="false" import="true" targetId="7046-7ca0-c93f-83e8" type="selectionEntry"/>
              </entryLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="40.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="6df5-a0b2-529f-61e4" name="Disco de Tzeentch (requiere Marca de Tzeentch)" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="7457-ec5f-3268-926a" type="max"/>
              </constraints>
              <entryLinks>
                <entryLink id="48a7-3d75-7e4f-2e17" name="Disco de Tzeentch" hidden="false" collective="false" import="true" targetId="3b3b-9456-d2c6-2a49" type="selectionEntry"/>
              </entryLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="45.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="2035-3fa4-287f-7ca6" name="Juggernaut de Khorne (requiere Marca de Khorne)" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="ee4a-d759-9d34-500f" type="max"/>
              </constraints>
              <entryLinks>
                <entryLink id="f082-0f93-bc8d-31f1" name="Juggernaut de Khorne" hidden="false" collective="false" import="true" targetId="219e-1929-41cd-c976" type="selectionEntry"/>
              </entryLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="55.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="50ee-2d88-f61c-24bb" name="Mant�cora" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="c6d7-63bb-8581-88dc" type="max"/>
              </constraints>
              <entryLinks>
                <entryLink id="db3c-fe29-83de-4af1" name="Mant�cora" hidden="false" collective="false" import="true" targetId="4e43-69c2-a267-15b8" type="selectionEntry"/>
              </entryLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="185.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="1033-019e-f9cb-1272" name="Drag�n del Caos (ocupa opci�n de h�roe adicional)" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="cdac-add9-b7f5-d7d2" type="max"/>
              </constraints>
              <entryLinks>
                <entryLink id="cc83-21f0-6056-7d66" name="Drag�n del Caos" hidden="false" collective="false" import="true" targetId="0471-db54-18c9-1d4f" type="selectionEntry"/>
              </entryLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="360.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="826c-6e2a-2821-247a" name="Inmundicia (requiere Marca de Nurgle)" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="9c32-32b8-de2c-10ee" type="max"/>
              </constraints>
              <entryLinks>
                <entryLink id="8b94-2dab-0450-e5c3" name="Inmundicia" hidden="false" collective="false" import="true" targetId="e4e8-dc8e-644b-a7dd" type="selectionEntry"/>
              </entryLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="220.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="0535-a7a8-d3e2-b1ea" name="Carro del Caos (requiere Marca correspondiente, ocupa unidad especial, sustituye a un miembro de la tripulaci�n)" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="03c5-29d3-4877-61ee" type="max"/>
              </constraints>
              <entryLinks>
                <entryLink id="c699-a195-86ff-9dd7" name="Carro del Caos" hidden="false" collective="false" import="true" targetId="90cc-5140-da19-7e49" type="selectionEntry"/>
              </entryLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="120.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="d543-6999-51be-5b90" name="Palanqu�n de Nurgle (requiere Marca de Nurgle)" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="c669-782b-d486-2675" type="max"/>
              </constraints>
              <entryLinks>
                <entryLink id="8193-b4cc-e577-3839" name="Palanqu�n de Nurgle" hidden="false" collective="false" import="true" targetId="67ae-144b-9780-bcc1" type="selectionEntry"/>
              </entryLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="50.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="091d-9733-e63a-6e20" name="Escudo" hidden="false" collective="false" import="true">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="d5f9-3b9a-1e03-1c8f" type="max"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="3216-f92f-9e4b-f982" name="Escudo" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="3b01-d222-50d9-49a4" type="max"/>
              </constraints>
              <infoLinks>
                <infoLink id="b3ee-3f4f-8642-2b60" name="Escudo" hidden="false" targetId="1e84-3cd7-87ca-0372" type="profile"/>
              </infoLinks>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="3.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
        <selectionEntryGroup id="287e-7e38-6e35-0b62" name="Marca del Caos" hidden="false" collective="false" import="true" defaultSelectionEntryId="311a-d375-dac1-6ac6">
          <constraints>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="26ab-a4fa-0f38-c79e" type="max"/>
            <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="4aa2-f7b9-301b-d454" type="min"/>
          </constraints>
          <selectionEntries>
            <selectionEntry id="311a-d375-dac1-6ac6" name="Marca del Caos absoluto" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="1020-a611-abad-b735" type="max"/>
              </constraints>
              <rules>
                <rule id="11e3-e862-9529-7ba3" name="Marca del Caos absoluto" hidden="false">
                  <description>El Se�or del Caos puede repetir cualquier chequeo de psicolog�a fallado.</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="0.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="ac81-97da-7d18-4af1" name="Marca de Khorne" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="1c1a-d825-a2c2-7ccb" type="max"/>
              </constraints>
              <rules>
                <rule id="1513-ebaf-d380-2a13" name="Marca de Khorne" hidden="false">
                  <description>El Se�or del Caos est� sujeto a Furia Asesina (pero no su montura). Mientras siga vivo, el ej�rcito tiene +1 dado de dispersi�n. Gana el tipo de unidad Khorne. Puede ir montado en un Juggernaut de Khorne (+55).</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="40.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="6a56-b363-8381-cc21" name="Marca de Nurgle" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="2221-239d-17b2-aad3" type="max"/>
              </constraints>
              <rules>
                <rule id="a29f-3d26-5928-cea6" name="Marca de Nurgle" hidden="false">
                  <description>El Se�or del Caos tiene H+1 y causa Miedo. Gana el tipo de unidad Nurgle. Puede ir montado en una Inmundicia (+220) o en un Palanqu�n de Nurgle (+50).</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="50.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="c953-e6ca-c597-212c" name="Marca de Tzeentch" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="e4b6-ad68-6da6-3f22" type="max"/>
              </constraints>
              <rules>
                <rule id="5972-c740-5590-f8b7" name="Marca de Tzeentch" hidden="false">
                  <description>El Se�or del Caos pasa a ser un hechicero de nivel 4 que debe usar el saber de Tzeentch. Puede lanzar hechizos pese a llevar armadura y/o escudo (normal o m�gica). Gana el tipo de unidad Tzeentch y el tipo de unidad Hechicero. Puede ir montado en un Disco de Tzeentch (+45).</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="140.0"/>
              </costs>
            </selectionEntry>
            <selectionEntry id="e387-71fd-f07f-d689" name="Marca de Slaanesh" hidden="false" collective="false" import="true" type="upgrade">
              <constraints>
                <constraint field="selections" scope="parent" value="1.0" percentValue="false" shared="true" includeChildSelections="false" includeChildForces="false" id="baea-bbef-c055-3833" type="max"/>
              </constraints>
              <rules>
                <rule id="b9c5-3e2f-635a-cd1d" name="Marca de Slaanesh" hidden="false">
                  <description>El Se�or del Caos es inmune a psicolog�a. Gana el tipo de unidad Slaanesh. Puede ir montado en un Diablo de Slaanesh (+40, no ocupa opci�n de unidad Especial).</description>
                </rule>
              </rules>
              <costs>
                <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="25.0"/>
              </costs>
            </selectionEntry>
          </selectionEntries>
        </selectionEntryGroup>
      </selectionEntryGroups>
      <costs>
        <cost name="puntos" typeId="53ea-00f4-9046-81ff" value="210.0"/>
      </costs>
    </selectionEntry>
    <selectionEntry id="fbbb-215c-3ced-8cf4" name="Gran hechicero del Caos" hidden="false" collective="false" import="true" type="model">
      <profiles>
        <profile id="410c-bf7e-5713-c3a0" name="Gran hechicero del Caos" hidden="false" typeId="1025-8460-b30f-58db" typeName="Modelo">
          <characteristics>
            <characteristic name="M" typeId="2d56-9cad-9242-37bd">10</characteristic>
            <characteristic name="HA" typeId="c87b-b820-6a47-1354">5</characteristic>
            <characteristic name="HP" typeId="8ab7-c800-6644-f5ec">3</characteristic>
            <characteristic name="F" typeId="79c2-0368-3eed-76b4">4</characteristic>
            <characteristic name="R" typeId="30bd-8385-2b51-e039">4</characteristic>
            <characteristic name="H" typeId="a41f-60f6-2336-73ab">3</characteristic>
            <characteristic name="I" typeId="fdd9-0cd1-90d5-1b6f">5</characteristic>
            <characteristic name="A" typeId="6b2b-37c4-6774-748b">2</characteristic>
            <characteristic name="L" typeId="458e-bb4b-f7c9-e0b3">8</characteristic>
            <characteristic name="TSA" typeId="2532-2940-06ec-7a6e">4+</characteristic>
            <characteristic name="Tipo" typeId="4a99-e6a0-4022-a833">Infanter�a, Humano, Caos, Hechicero</characteristic>
            <characteristic name="Potencia" typeId="6bbb-9823-b0cd-5705">1</characteristic>
          </characteristics>
        </profile>
      </profiles>
