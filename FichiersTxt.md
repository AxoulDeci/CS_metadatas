<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.file.server" id="_HfTNAHSxEe6Cj7jyPVDy-A" name="Source" md:ref="resource.md#UUID_TECH_FILE_MD?fileId=UUID_TECH_FILE_MD$type=md$name=File?" internalVersion="v1.0.0">
  <node defType="com.stambia.file.directory" id="_HhMDYHSxEe6Cj7jyPVDy-A" name="F_CLIENT">
    <attribute defType="com.stambia.file.directory.path" id="_dc5y4Ho6Ee6i1bEIfNaCgQ" value="C:\source"/>
    <node defType="com.stambia.file.file" id="_HhUmQHSxEe6Cj7jyPVDy-A" name="F_CLIENT">
      <attribute defType="com.stambia.file.file.type" id="_Hh51EHSxEe6Cj7jyPVDy-A" value="DELIMITED"/>
      <attribute defType="com.stambia.file.file.lineSeparator" id="_Hh7qQHSxEe6Cj7jyPVDy-A" value="0A"/>
      <attribute defType="com.stambia.file.file.fieldSeparator" id="_Hh7qQXSxEe6Cj7jyPVDy-A" value="7C"/>
      <attribute defType="com.stambia.file.file.decimalSeparator" id="_Hh8RUHSxEe6Cj7jyPVDy-A" value="2E"/>
      <attribute defType="com.stambia.file.file.lineToSkip" id="_Hh84YXSxEe6Cj7jyPVDy-A" value="0"/>
      <attribute defType="com.stambia.file.file.lastLineToSkip" id="_Hh9fcHSxEe6Cj7jyPVDy-A" value="0"/>
      <attribute defType="com.stambia.file.file.header" id="_Hh9fcXSxEe6Cj7jyPVDy-A" value="0"/>
      <attribute defType="com.stambia.file.file.physicalName" id="_V_GecHSxEe6Cj7jyPVDy-A" value="F_CLIENT_*.txt"/>
      <attribute defType="com.stambia.file.file.charsetName" id="_IuN18Ho9Ee6mjOH6QyZAxg" value="UTF-8"/>
      <node defType="com.stambia.file.record" id="_vFq6QXSxEe6Cj7jyPVDy-A" name="COMPTE">
        <node defType="com.stambia.file.filter" id="_rD1nEXSyEe6Cj7jyPVDy-A" name="CRITERE">
          <attribute defType="com.stambia.file.filter.value" id="_1escYHSyEe6Cj7jyPVDy-A" value="100"/>
          <attribute defType="com.stambia.file.filter.start" id="_BnYsgHSzEe6Cj7jyPVDy-A" value="1"/>
          <attribute defType="com.stambia.file.filter.length" id="_B7kz0HSzEe6Cj7jyPVDy-A" value="3"/>
          <attribute defType="com.stambia.file.filter.operator" id="_7kk7oHo7Ee6i1bEIfNaCgQ" value="Equals"/>
        </node>
        <node defType="com.stambia.file.field" id="_Gb_okHolEe62SbngGOCG7g" name="TYPE_LIGNE" position="1">
          <attribute defType="com.stambia.file.field.physicalName" id="_GcKnsHolEe62SbngGOCG7g" value="TYPE_LIGNE"/>
          <attribute defType="com.stambia.file.field.type" id="_GcKnsXolEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_GcKnsnolEe62SbngGOCG7g" value="3"/>
        </node>
        <node defType="com.stambia.file.field" id="_Gd_MoHolEe62SbngGOCG7g" name="ACTION" position="2">
          <attribute defType="com.stambia.file.field.physicalName" id="_GeEsMHolEe62SbngGOCG7g" value="ACTION"/>
          <attribute defType="com.stambia.file.field.type" id="_GeEsMXolEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_GeEsMnolEe62SbngGOCG7g" value="1"/>
        </node>
        <node defType="com.stambia.file.field" id="_Hq8vAHolEe62SbngGOCG7g" name="CLE_COMPTE" position="3">
          <attribute defType="com.stambia.file.field.physicalName" id="_Hq-kMHolEe62SbngGOCG7g" value="CLE_COMPTE"/>
          <attribute defType="com.stambia.file.field.type" id="_Hq-kMXolEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_Hq-kMnolEe62SbngGOCG7g" value="45"/>
        </node>
        <node defType="com.stambia.file.field" id="_Hsx7AHolEe62SbngGOCG7g" name="STATUS" position="4">
          <attribute defType="com.stambia.file.field.physicalName" id="_Hs4osHolEe62SbngGOCG7g" value="STATUS"/>
          <attribute defType="com.stambia.file.field.type" id="_Hs5PwHolEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_Hs5PwXolEe62SbngGOCG7g" value="5"/>
        </node>
        <node defType="com.stambia.file.field" id="_H5VJQHolEe62SbngGOCG7g" name="TYPE" position="5">
          <attribute defType="com.stambia.file.field.physicalName" id="_H5eTMHolEe62SbngGOCG7g" value="TYPE"/>
          <attribute defType="com.stambia.file.field.type" id="_H5eTMXolEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_H5e6QHolEe62SbngGOCG7g" value="5"/>
        </node>
        <node defType="com.stambia.file.field" id="_UOZBcHolEe62SbngGOCG7g" name="CABINET_RATTACHEMENT" position="6">
          <attribute defType="com.stambia.file.field.physicalName" id="_UOcEwHolEe62SbngGOCG7g" value="CABINET_RATTACHEMENT"/>
          <attribute defType="com.stambia.file.field.type" id="_UOcEwXolEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_UOcEwnolEe62SbngGOCG7g" value="9"/>
        </node>
      </node>
      <node defType="com.stambia.file.propertyField" id="_wblkVHSxEe6Cj7jyPVDy-A" name="file_name">
        <attribute defType="com.stambia.file.propertyField.property" id="_yWcugHSxEe6Cj7jyPVDy-A" value="file_name"/>
      </node>
      <node defType="com.stambia.file.record" id="_-mDe8XSxEe6Cj7jyPVDy-A" name="CLIENT">
        <node defType="com.stambia.file.filter" id="_nbXrkXSyEe6Cj7jyPVDy-A" name="CRITERE">
          <attribute defType="com.stambia.file.filter.value" id="_yax_cHSyEe6Cj7jyPVDy-A" value="200"/>
          <attribute defType="com.stambia.file.filter.start" id="_A-s74HSzEe6Cj7jyPVDy-A" value="1"/>
          <attribute defType="com.stambia.file.filter.length" id="_BU5OUHSzEe6Cj7jyPVDy-A" value="3"/>
          <attribute defType="com.stambia.file.filter.operator" id="_6Iv20Ho7Ee6i1bEIfNaCgQ" value="Equals"/>
        </node>
        <node defType="com.stambia.file.field" id="_4NY_YHolEe62SbngGOCG7g" name="TYPE_LIGNE" position="1">
          <attribute defType="com.stambia.file.field.physicalName" id="_4NY_YXolEe62SbngGOCG7g" value="TYPE_LIGNE"/>
          <attribute defType="com.stambia.file.field.type" id="_4NY_YnolEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_4NY_Y3olEe62SbngGOCG7g" value="3"/>
        </node>
        <node defType="com.stambia.file.field" id="_4O-60HolEe62SbngGOCG7g" name="ACTION" position="2">
          <attribute defType="com.stambia.file.field.physicalName" id="_4O_h4HolEe62SbngGOCG7g" value="ACTION"/>
          <attribute defType="com.stambia.file.field.type" id="_4O_h4XolEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_4O_h4nolEe62SbngGOCG7g" value="1"/>
        </node>
        <node defType="com.stambia.file.field" id="_4cGw0HolEe62SbngGOCG7g" name="CLE_CLIENT" position="3">
          <attribute defType="com.stambia.file.field.physicalName" id="_4cHX4HolEe62SbngGOCG7g" value="CLE_CLIENT"/>
          <attribute defType="com.stambia.file.field.type" id="_4cHX4XolEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_4cHX4nolEe62SbngGOCG7g" value="45"/>
        </node>
        <node defType="com.stambia.file.field" id="_4hmU0HolEe62SbngGOCG7g" name="CLE_COMPTE" position="4">
          <attribute defType="com.stambia.file.field.physicalName" id="_4hm74HolEe62SbngGOCG7g" value="CLE_COMPTE"/>
          <attribute defType="com.stambia.file.field.type" id="_4hm74XolEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_4hm74nolEe62SbngGOCG7g" value="45"/>
        </node>
        <node defType="com.stambia.file.field" id="_4mZ8UHolEe62SbngGOCG7g" name="STATUS" position="5">
          <attribute defType="com.stambia.file.field.physicalName" id="_4majYHolEe62SbngGOCG7g" value="STATUS"/>
          <attribute defType="com.stambia.file.field.type" id="_4mbKcHolEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_4mbKcXolEe62SbngGOCG7g" value="5"/>
        </node>
        <node defType="com.stambia.file.field" id="_4rl-UHolEe62SbngGOCG7g" name="TYPE" position="6">
          <attribute defType="com.stambia.file.field.physicalName" id="_4rmlYHolEe62SbngGOCG7g" value="TYPE"/>
          <attribute defType="com.stambia.file.field.type" id="_4rmlYXolEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_4rmlYnolEe62SbngGOCG7g" value="5"/>
        </node>
        <node defType="com.stambia.file.field" id="_4xd80HolEe62SbngGOCG7g" name="CIVILITE" position="7">
          <attribute defType="com.stambia.file.field.physicalName" id="_4xej4HolEe62SbngGOCG7g" value="CIVILITE"/>
          <attribute defType="com.stambia.file.field.type" id="_4xej4XolEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_4xej4nolEe62SbngGOCG7g" value="5"/>
        </node>
        <node defType="com.stambia.file.field" id="_43V7UHolEe62SbngGOCG7g" name="PRENOM" position="8">
          <attribute defType="com.stambia.file.field.physicalName" id="_43WiYHolEe62SbngGOCG7g" value="PRENOM"/>
          <attribute defType="com.stambia.file.field.type" id="_43WiYXolEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_43WiYnolEe62SbngGOCG7g" value="255"/>
        </node>
        <node defType="com.stambia.file.field" id="_48_QUHolEe62SbngGOCG7g" name="NOM" position="9">
          <attribute defType="com.stambia.file.field.physicalName" id="_48_3YHolEe62SbngGOCG7g" value="NOM"/>
          <attribute defType="com.stambia.file.field.type" id="_48_3YXolEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_48_3YnolEe62SbngGOCG7g" value="255"/>
        </node>
        <node defType="com.stambia.file.field" id="_5Fwx0HolEe62SbngGOCG7g" name="DATE_ANNIVERSAIRE" position="10">
          <attribute defType="com.stambia.file.field.physicalName" id="_5Fx_8HolEe62SbngGOCG7g" value="DATE_ANNIVERSAIRE"/>
          <attribute defType="com.stambia.file.field.type" id="_5Fx_8XolEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_5Fx_8nolEe62SbngGOCG7g" value="10"/>
        </node>
        <node defType="com.stambia.file.field" id="_5LGk0HolEe62SbngGOCG7g" name="SEXE" position="11">
          <attribute defType="com.stambia.file.field.physicalName" id="_5LHL4HolEe62SbngGOCG7g" value="SEXE"/>
          <attribute defType="com.stambia.file.field.type" id="_5LHL4XolEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_5LHL4nolEe62SbngGOCG7g" value="5"/>
        </node>
        <node defType="com.stambia.file.field" id="_5PTIUHolEe62SbngGOCG7g" name="MUTUELLE" position="12">
          <attribute defType="com.stambia.file.field.physicalName" id="_5PTvYHolEe62SbngGOCG7g" value="MUTUELLE"/>
          <attribute defType="com.stambia.file.field.type" id="_5PTvYXolEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_5PTvYnolEe62SbngGOCG7g" value="5"/>
        </node>
      </node>
      <node defType="com.stambia.file.record" id="_AIErUXSyEe6Cj7jyPVDy-A" name="EMAIL">
        <node defType="com.stambia.file.filter" id="_roE8kXSyEe6Cj7jyPVDy-A" name="CRITERE">
          <attribute defType="com.stambia.file.filter.value" id="_2luV4HSyEe6Cj7jyPVDy-A" value="203"/>
          <attribute defType="com.stambia.file.filter.start" id="_CQjlUHSzEe6Cj7jyPVDy-A" value="1"/>
          <attribute defType="com.stambia.file.filter.length" id="_CecQUHSzEe6Cj7jyPVDy-A" value="3"/>
          <attribute defType="com.stambia.file.filter.operator" id="_84lhMHo7Ee6i1bEIfNaCgQ" value="Equals"/>
        </node>
        <node defType="com.stambia.file.field" id="_V0dK4HomEe62SbngGOCG7g" name="TYPE_LIGNE" position="1">
          <attribute defType="com.stambia.file.field.physicalName" id="_V0dx8HomEe62SbngGOCG7g" value="TYPE_LIGNE"/>
          <attribute defType="com.stambia.file.field.type" id="_V0dx8XomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_V0dx8nomEe62SbngGOCG7g" value="3"/>
        </node>
        <node defType="com.stambia.file.field" id="_V1-N0HomEe62SbngGOCG7g" name="ACTION" position="2">
          <attribute defType="com.stambia.file.field.physicalName" id="_V1_b8HomEe62SbngGOCG7g" value="ACTION"/>
          <attribute defType="com.stambia.file.field.type" id="_V1_b8XomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_V1_b8nomEe62SbngGOCG7g" value="1"/>
        </node>
        <node defType="com.stambia.file.field" id="_V5teUHomEe62SbngGOCG7g" name="CLE_CLIENT" position="3">
          <attribute defType="com.stambia.file.field.physicalName" id="_V5uFYHomEe62SbngGOCG7g" value="CLE_CLIENT"/>
          <attribute defType="com.stambia.file.field.type" id="_V5uFYXomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_V5uFYnomEe62SbngGOCG7g" value="45"/>
        </node>
        <node defType="com.stambia.file.field" id="_V7Un4HomEe62SbngGOCG7g" name="EMAIL_LIB" position="4">
          <attribute defType="com.stambia.file.field.physicalName" id="_V7Un4XomEe62SbngGOCG7g" value="EMAIL"/>
          <attribute defType="com.stambia.file.field.type" id="_V7Un4nomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_V7Un43omEe62SbngGOCG7g" value="255"/>
        </node>
        <node defType="com.stambia.file.field" id="_WBCOUHomEe62SbngGOCG7g" name="STATUS" position="5">
          <attribute defType="com.stambia.file.field.physicalName" id="_WBC1YHomEe62SbngGOCG7g" value="STATUS"/>
          <attribute defType="com.stambia.file.field.type" id="_WBC1YXomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_WBC1YnomEe62SbngGOCG7g" value="5"/>
        </node>
      </node>
      <node defType="com.stambia.file.record" id="_AsBF4XSyEe6Cj7jyPVDy-A" name="ADRESSE">
        <node defType="com.stambia.file.filter" id="_v8rawnSxEe6Cj7jyPVDy-A" name="CRITERE">
          <attribute defType="com.stambia.file.filter.value" id="_xdROUHSyEe6Cj7jyPVDy-A" value="204"/>
          <attribute defType="com.stambia.file.filter.start" id="_AbGfkHSzEe6Cj7jyPVDy-A" value="1"/>
          <attribute defType="com.stambia.file.filter.length" id="_Awp40HSzEe6Cj7jyPVDy-A" value="3"/>
          <attribute defType="com.stambia.file.filter.operator" id="_5Ow60Ho7Ee6i1bEIfNaCgQ" value="Equals"/>
        </node>
        <node defType="com.stambia.file.field" id="_jgigYHomEe62SbngGOCG7g" name="TYPE_LIGNE" position="1">
          <attribute defType="com.stambia.file.field.physicalName" id="_jgjHcHomEe62SbngGOCG7g" value="TYPE_LIGNE"/>
          <attribute defType="com.stambia.file.field.type" id="_jgjHcXomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_jgjHcnomEe62SbngGOCG7g" value="3"/>
        </node>
        <node defType="com.stambia.file.field" id="_jkz8YHomEe62SbngGOCG7g" name="ACTION" position="2">
          <attribute defType="com.stambia.file.field.physicalName" id="_jk0jcHomEe62SbngGOCG7g" value="ACTION"/>
          <attribute defType="com.stambia.file.field.type" id="_jk0jcXomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_jk0jcnomEe62SbngGOCG7g" value="1"/>
        </node>
        <node defType="com.stambia.file.field" id="_jscOYHomEe62SbngGOCG7g" name="CLE_CLIENT" position="3">
          <attribute defType="com.stambia.file.field.physicalName" id="_jsc1cHomEe62SbngGOCG7g" value="CLE_CLIENT"/>
          <attribute defType="com.stambia.file.field.type" id="_jsc1cXomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_jsc1cnomEe62SbngGOCG7g" value="45"/>
        </node>
        <node defType="com.stambia.file.field" id="_jyi2YHomEe62SbngGOCG7g" name="STATUS" position="4">
          <attribute defType="com.stambia.file.field.physicalName" id="_jyjdcHomEe62SbngGOCG7g" value="STATUS"/>
          <attribute defType="com.stambia.file.field.type" id="_jyjdcXomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_jyjdcnomEe62SbngGOCG7g" value="5"/>
        </node>
        <node defType="com.stambia.file.field" id="_j49AYHomEe62SbngGOCG7g" name="LIGNE_1" position="5">
          <attribute defType="com.stambia.file.field.physicalName" id="_j49ncHomEe62SbngGOCG7g" value="LIGNE_1"/>
          <attribute defType="com.stambia.file.field.type" id="_j49ncXomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_j49ncnomEe62SbngGOCG7g" value="255"/>
        </node>
        <node defType="com.stambia.file.field" id="_j_-OYHomEe62SbngGOCG7g" name="LIGNE_2" position="6">
          <attribute defType="com.stambia.file.field.physicalName" id="_j_-1cHomEe62SbngGOCG7g" value="LIGNE_2"/>
          <attribute defType="com.stambia.file.field.type" id="_j_-1cXomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_j_-1cnomEe62SbngGOCG7g" value="255"/>
        </node>
        <node defType="com.stambia.file.field" id="_kGwy4HomEe62SbngGOCG7g" name="LIGNE_3" position="7">
          <attribute defType="com.stambia.file.field.physicalName" id="_kGxZ8HomEe62SbngGOCG7g" value="LIGNE_3"/>
          <attribute defType="com.stambia.file.field.type" id="_kGxZ8XomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_kGxZ8nomEe62SbngGOCG7g" value="255"/>
        </node>
        <node defType="com.stambia.file.field" id="_kOUMYHomEe62SbngGOCG7g" name="LIGNE_4" position="8">
          <attribute defType="com.stambia.file.field.physicalName" id="_kOUzcHomEe62SbngGOCG7g" value="LIGNE_4"/>
          <attribute defType="com.stambia.file.field.type" id="_kOUzcXomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_kOUzcnomEe62SbngGOCG7g" value="255"/>
        </node>
        <node defType="com.stambia.file.field" id="_kV3l4HomEe62SbngGOCG7g" name="LIGNE_5" position="9">
          <attribute defType="com.stambia.file.field.physicalName" id="_kV4M8HomEe62SbngGOCG7g" value="LIGNE_5"/>
          <attribute defType="com.stambia.file.field.type" id="_kV4M8XomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_kV4M8nomEe62SbngGOCG7g" value="255"/>
        </node>
        <node defType="com.stambia.file.field" id="_kcDGYHomEe62SbngGOCG7g" name="VILLE" position="10">
          <attribute defType="com.stambia.file.field.physicalName" id="_kcDtcHomEe62SbngGOCG7g" value="VILLE"/>
          <attribute defType="com.stambia.file.field.type" id="_kcDtcXomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_kcDtcnomEe62SbngGOCG7g" value="50"/>
        </node>
        <node defType="com.stambia.file.field" id="_kiE14HomEe62SbngGOCG7g" name="CODE_POSTAL" position="11">
          <attribute defType="com.stambia.file.field.physicalName" id="_kiFc8HomEe62SbngGOCG7g" value="CODE_POSTAL"/>
          <attribute defType="com.stambia.file.field.type" id="_kiGEAHomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_kiGEAXomEe62SbngGOCG7g" value="10"/>
        </node>
        <node defType="com.stambia.file.field" id="_koyh4HomEe62SbngGOCG7g" name="PAYS" position="12">
          <attribute defType="com.stambia.file.field.physicalName" id="_kozI8HomEe62SbngGOCG7g" value="PAYS"/>
          <attribute defType="com.stambia.file.field.type" id="_kozI8XomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_kozI8nomEe62SbngGOCG7g" value="5"/>
        </node>
        <node defType="com.stambia.file.field" id="_kugvYHomEe62SbngGOCG7g" name="QUALITE" position="13">
          <attribute defType="com.stambia.file.field.physicalName" id="_kuhWcHomEe62SbngGOCG7g" value="QUALITE"/>
          <attribute defType="com.stambia.file.field.type" id="_kuhWcXomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_kuhWcnomEe62SbngGOCG7g" value="5"/>
        </node>
      </node>
      <node defType="com.stambia.file.record" id="_BJj9gXSyEe6Cj7jyPVDy-A" name="TEL">
        <node defType="com.stambia.file.filter" id="_r-gfkXSyEe6Cj7jyPVDy-A" name="CRITERE">
          <attribute defType="com.stambia.file.filter.value" id="_3jSKUHSyEe6Cj7jyPVDy-A" value="205"/>
          <attribute defType="com.stambia.file.filter.start" id="_CstV0HSzEe6Cj7jyPVDy-A" value="1"/>
          <attribute defType="com.stambia.file.filter.length" id="_C-ykUHSzEe6Cj7jyPVDy-A" value="3"/>
          <attribute defType="com.stambia.file.filter.operator" id="_9vzdEHo7Ee6i1bEIfNaCgQ" value="Equals"/>
        </node>
        <node defType="com.stambia.file.field" id="_6lvhYHomEe62SbngGOCG7g" name="TYPE_LIGNE" position="1">
          <attribute defType="com.stambia.file.field.physicalName" id="_6lwIcHomEe62SbngGOCG7g" value="TYPE_LIGNE"/>
          <attribute defType="com.stambia.file.field.type" id="_6lwIcXomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_6lwIcnomEe62SbngGOCG7g" value="3"/>
        </node>
        <node defType="com.stambia.file.field" id="_6wbHYHomEe62SbngGOCG7g" name="ACTION" position="2">
          <attribute defType="com.stambia.file.field.physicalName" id="_6wbucHomEe62SbngGOCG7g" value="ACTION"/>
          <attribute defType="com.stambia.file.field.type" id="_6wbucXomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_6wbucnomEe62SbngGOCG7g" value="1"/>
        </node>
        <node defType="com.stambia.file.field" id="_62ONYHomEe62SbngGOCG7g" name="CLE_CLIENT" position="3">
          <attribute defType="com.stambia.file.field.physicalName" id="_62O0cHomEe62SbngGOCG7g" value="CLE_CLIENT"/>
          <attribute defType="com.stambia.file.field.type" id="_62O0cXomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_62O0cnomEe62SbngGOCG7g" value="45"/>
        </node>
        <node defType="com.stambia.file.field" id="_7aibYHomEe62SbngGOCG7g" name="PHONE" position="4">
          <attribute defType="com.stambia.file.field.physicalName" id="_7ajCcHomEe62SbngGOCG7g" value="PHONE"/>
          <attribute defType="com.stambia.file.field.type" id="_7ajCcXomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_7ajCcnomEe62SbngGOCG7g" value="45"/>
        </node>
        <node defType="com.stambia.file.field" id="_7hQHYHomEe62SbngGOCG7g" name="STATUS" position="5">
          <attribute defType="com.stambia.file.field.physicalName" id="_7hQucHomEe62SbngGOCG7g" value="STATUS"/>
          <attribute defType="com.stambia.file.field.type" id="_7hQucXomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_7hQucnomEe62SbngGOCG7g" value="5"/>
        </node>
        <node defType="com.stambia.file.field" id="_7oCr4HomEe62SbngGOCG7g" name="FAVORI" position="6">
          <attribute defType="com.stambia.file.field.physicalName" id="_7oDS8HomEe62SbngGOCG7g" value="FAVORI"/>
          <attribute defType="com.stambia.file.field.type" id="_7oDS8XomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_7oDS8nomEe62SbngGOCG7g" value="5"/>
        </node>
        <node defType="com.stambia.file.field" id="_7roycHomEe62SbngGOCG7g" name="TYPE" position="7">
          <attribute defType="com.stambia.file.field.physicalName" id="_7rpZgHomEe62SbngGOCG7g" value="TYPE"/>
          <attribute defType="com.stambia.file.field.type" id="_7rpZgXomEe62SbngGOCG7g" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_7rpZgnomEe62SbngGOCG7g" value="5"/>
        </node>
      </node>
      <node defType="com.stambia.file.record" id="_SbAtIX-oEe6IE6AcCtnNjw" name="ENTETE">
        <node defType="com.stambia.file.field" id="_2bUSoH-oEe6IE6AcCtnNjw" name="TYPE_LIGNE" position="1">
          <attribute defType="com.stambia.file.field.physicalName" id="_2bU5sH-oEe6IE6AcCtnNjw" value="TYPE_LIGNE"/>
          <attribute defType="com.stambia.file.field.type" id="_2bU5sX-oEe6IE6AcCtnNjw" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_2bU5sn-oEe6IE6AcCtnNjw" value="3"/>
          <attribute defType="com.stambia.file.field.physicalSize" id="_K34LgH-rEe6IE6AcCtnNjw" value="3"/>
        </node>
        <node defType="com.stambia.file.field" id="_2c61IH-oEe6IE6AcCtnNjw" name="TYPE_FICHIER" position="2">
          <attribute defType="com.stambia.file.field.physicalName" id="_2c8DQH-oEe6IE6AcCtnNjw" value="TYPE_FICHIER"/>
          <attribute defType="com.stambia.file.field.type" id="_2c8DQX-oEe6IE6AcCtnNjw" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_2c8DQn-oEe6IE6AcCtnNjw" value="20"/>
          <attribute defType="com.stambia.file.field.physicalSize" id="_LDeXgH-rEe6IE6AcCtnNjw" value="20"/>
        </node>
        <node defType="com.stambia.file.field" id="_2eSuIH-oEe6IE6AcCtnNjw" name="VERSION" position="3">
          <attribute defType="com.stambia.file.field.physicalName" id="_2eTVMH-oEe6IE6AcCtnNjw" value="VERSION"/>
          <attribute defType="com.stambia.file.field.type" id="_2eTVMX-oEe6IE6AcCtnNjw" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_2eTVMn-oEe6IE6AcCtnNjw" value="2"/>
          <attribute defType="com.stambia.file.field.physicalSize" id="_LRdJIH-rEe6IE6AcCtnNjw" value="2"/>
        </node>
        <node defType="com.stambia.file.field" id="_2fvfoH-oEe6IE6AcCtnNjw" name="DATE" position="4">
          <attribute defType="com.stambia.file.field.physicalName" id="_2fwGsH-oEe6IE6AcCtnNjw" value="DATE"/>
          <attribute defType="com.stambia.file.field.type" id="_2fwGsX-oEe6IE6AcCtnNjw" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_2fwGsn-oEe6IE6AcCtnNjw" value="30"/>
          <attribute defType="com.stambia.file.field.physicalSize" id="_LarWkH-rEe6IE6AcCtnNjw" value="30"/>
        </node>
        <node defType="com.stambia.file.field" id="_2iVgoH-oEe6IE6AcCtnNjw" name="SOURCE" position="5">
          <attribute defType="com.stambia.file.field.physicalName" id="_2iWHsH-oEe6IE6AcCtnNjw" value="SOURCE"/>
          <attribute defType="com.stambia.file.field.type" id="_2iWHsX-oEe6IE6AcCtnNjw" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_2iWHsn-oEe6IE6AcCtnNjw" value="30"/>
          <attribute defType="com.stambia.file.field.physicalSize" id="_Lk3NUH-rEe6IE6AcCtnNjw" value="30"/>
        </node>
        <node defType="com.stambia.file.field" id="_2jtZoH-oEe6IE6AcCtnNjw" name="SEQUENCE" position="6">
          <attribute defType="com.stambia.file.field.physicalName" id="_2jtZoX-oEe6IE6AcCtnNjw" value="SEQUENCE"/>
          <attribute defType="com.stambia.file.field.type" id="_2jtZon-oEe6IE6AcCtnNjw" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_2jtZo3-oEe6IE6AcCtnNjw" value="8"/>
          <attribute defType="com.stambia.file.field.physicalSize" id="_L97NkH-rEe6IE6AcCtnNjw" value="8"/>
        </node>
        <node defType="com.stambia.file.filter" id="_ev7l9X-pEe6IE6AcCtnNjw" name="CRITERE">
          <attribute defType="com.stambia.file.filter.value" id="_ev7l9n-pEe6IE6AcCtnNjw" value="000"/>
          <attribute defType="com.stambia.file.filter.start" id="_ev7l93-pEe6IE6AcCtnNjw" value="1"/>
          <attribute defType="com.stambia.file.filter.length" id="_ev7l-H-pEe6IE6AcCtnNjw" value="3"/>
          <attribute defType="com.stambia.file.filter.operator" id="_ev7l-X-pEe6IE6AcCtnNjw" value="Equals"/>
        </node>
      </node>
      <node defType="com.stambia.file.record" id="_UB058X-oEe6IE6AcCtnNjw" name="PIED">
        <node defType="com.stambia.file.field" id="_irDXsH-pEe6IE6AcCtnNjw" name="TYPE_LIGNE" position="1">
          <attribute defType="com.stambia.file.field.physicalName" id="_irD-wH-pEe6IE6AcCtnNjw" value="TYPE_LIGNE"/>
          <attribute defType="com.stambia.file.field.type" id="_irD-wX-pEe6IE6AcCtnNjw" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_irD-wn-pEe6IE6AcCtnNjw" value="3"/>
        </node>
        <node defType="com.stambia.file.field" id="_isapoH-pEe6IE6AcCtnNjw" name="NB_LIGNE" position="2">
          <attribute defType="com.stambia.file.field.physicalName" id="_isbQsH-pEe6IE6AcCtnNjw" value="NB_LIGNE"/>
          <attribute defType="com.stambia.file.field.type" id="_isbQsX-pEe6IE6AcCtnNjw" value="String"/>
          <attribute defType="com.stambia.file.field.size" id="_isbQsn-pEe6IE6AcCtnNjw" value="10"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.file.file" id="_smFd8IqgEe6wS8JTT7vucg" name="F_CLIENT_CHECK">
      <attribute defType="com.stambia.file.file.type" id="_smFd8YqgEe6wS8JTT7vucg" value="DELIMITED"/>
      <attribute defType="com.stambia.file.file.lineSeparator" id="_smFd84qgEe6wS8JTT7vucg" value="0D0A"/>
      <attribute defType="com.stambia.file.file.fieldSeparator" id="_smFd9IqgEe6wS8JTT7vucg" value="7C"/>
      <attribute defType="com.stambia.file.file.decimalSeparator" id="_smFd9oqgEe6wS8JTT7vucg" value="2E"/>
      <attribute defType="com.stambia.file.file.lineToSkip" id="_smFd-IqgEe6wS8JTT7vucg" value="0"/>
      <attribute defType="com.stambia.file.file.lastLineToSkip" id="_smFd-YqgEe6wS8JTT7vucg" value="0"/>
      <attribute defType="com.stambia.file.file.header" id="_smFd-oqgEe6wS8JTT7vucg" value="0"/>
      <attribute defType="com.stambia.file.file.physicalName" id="_smFd-4qgEe6wS8JTT7vucg" value="F_CLIENT_*.txt"/>
      <node defType="com.stambia.file.field" id="_smFd_IqgEe6wS8JTT7vucg" name="F6" position="6">
        <attribute defType="com.stambia.file.field.size" id="_smFd_YqgEe6wS8JTT7vucg" value="64"/>
        <attribute defType="com.stambia.file.field.type" id="_smFd_oqgEe6wS8JTT7vucg" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_smFd_4qgEe6wS8JTT7vucg" value="F6"/>
      </node>
      <node defType="com.stambia.file.field" id="_smFeAIqgEe6wS8JTT7vucg" name="F2" position="2">
        <attribute defType="com.stambia.file.field.size" id="_smFeAYqgEe6wS8JTT7vucg" value="56"/>
        <attribute defType="com.stambia.file.field.type" id="_smFeAoqgEe6wS8JTT7vucg" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_smFeA4qgEe6wS8JTT7vucg" value="F2"/>
      </node>
      <node defType="com.stambia.file.field" id="_smFeBIqgEe6wS8JTT7vucg" name="F5" position="5">
        <attribute defType="com.stambia.file.field.size" id="_smFeBYqgEe6wS8JTT7vucg" value="54"/>
        <attribute defType="com.stambia.file.field.type" id="_smFeBoqgEe6wS8JTT7vucg" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_smFeB4qgEe6wS8JTT7vucg" value="F5"/>
      </node>
      <node defType="com.stambia.file.field" id="_smFeCIqgEe6wS8JTT7vucg" name="F4" position="4">
        <attribute defType="com.stambia.file.field.size" id="_smFeCYqgEe6wS8JTT7vucg" value="71"/>
        <attribute defType="com.stambia.file.field.type" id="_smFeCoqgEe6wS8JTT7vucg" value="String"/>
        <attribute defType="com.stambia.file.field.format" id="_smFeC4qgEe6wS8JTT7vucg" value="yyyy-MM-dd"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_smFeDIqgEe6wS8JTT7vucg" value="F4"/>
      </node>
      <node defType="com.stambia.file.field" id="_smFeDYqgEe6wS8JTT7vucg" name="F3" position="3">
        <attribute defType="com.stambia.file.field.size" id="_smFeDoqgEe6wS8JTT7vucg" value="59"/>
        <attribute defType="com.stambia.file.field.type" id="_smFeD4qgEe6wS8JTT7vucg" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_smFeEIqgEe6wS8JTT7vucg" value="F3"/>
      </node>
      <node defType="com.stambia.file.field" id="_smFeEYqgEe6wS8JTT7vucg" name="F1" position="1">
        <attribute defType="com.stambia.file.field.size" id="_smFeEoqgEe6wS8JTT7vucg" value="12"/>
        <attribute defType="com.stambia.file.field.type" id="_smFeE4qgEe6wS8JTT7vucg" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_smFeFIqgEe6wS8JTT7vucg" value="F1"/>
      </node>
      <node defType="com.stambia.file.field" id="_smFeFYqgEe6wS8JTT7vucg" name="F7" position="7">
        <attribute defType="com.stambia.file.field.physicalName" id="_smFeFoqgEe6wS8JTT7vucg" value="F7"/>
        <attribute defType="com.stambia.file.field.type" id="_smFeF4qgEe6wS8JTT7vucg" value="String"/>
        <attribute defType="com.stambia.file.field.size" id="_smFeGIqgEe6wS8JTT7vucg" value="50"/>
      </node>
      <node defType="com.stambia.file.field" id="_smFeGYqgEe6wS8JTT7vucg" name="F8" position="8">
        <attribute defType="com.stambia.file.field.physicalName" id="_smFeGoqgEe6wS8JTT7vucg" value="F8"/>
        <attribute defType="com.stambia.file.field.type" id="_smFeG4qgEe6wS8JTT7vucg" value="String"/>
        <attribute defType="com.stambia.file.field.size" id="_smFeHIqgEe6wS8JTT7vucg" value="50"/>
      </node>
      <node defType="com.stambia.file.field" id="_smFeHYqgEe6wS8JTT7vucg" name="F9" position="9">
        <attribute defType="com.stambia.file.field.physicalName" id="_smFeHoqgEe6wS8JTT7vucg" value="F9"/>
        <attribute defType="com.stambia.file.field.type" id="_smFeH4qgEe6wS8JTT7vucg" value="String"/>
        <attribute defType="com.stambia.file.field.size" id="_smFeIIqgEe6wS8JTT7vucg" value="50"/>
      </node>
      <node defType="com.stambia.file.field" id="_smFeIYqgEe6wS8JTT7vucg" name="F10" position="10">
        <attribute defType="com.stambia.file.field.physicalName" id="_smFeIoqgEe6wS8JTT7vucg" value="F10"/>
        <attribute defType="com.stambia.file.field.type" id="_smFeI4qgEe6wS8JTT7vucg" value="String"/>
        <attribute defType="com.stambia.file.field.size" id="_smFeJIqgEe6wS8JTT7vucg" value="50"/>
      </node>
      <node defType="com.stambia.file.field" id="_smFeJYqgEe6wS8JTT7vucg" name="F11" position="11">
        <attribute defType="com.stambia.file.field.physicalName" id="_smFeJoqgEe6wS8JTT7vucg" value="F11"/>
        <attribute defType="com.stambia.file.field.type" id="_smFeJ4qgEe6wS8JTT7vucg" value="String"/>
        <attribute defType="com.stambia.file.field.size" id="_smFeKIqgEe6wS8JTT7vucg" value="50"/>
      </node>
      <node defType="com.stambia.file.field" id="_smFeKYqgEe6wS8JTT7vucg" name="F12" position="12">
        <attribute defType="com.stambia.file.field.physicalName" id="_smFeKoqgEe6wS8JTT7vucg" value="F12"/>
        <attribute defType="com.stambia.file.field.type" id="_smGFAIqgEe6wS8JTT7vucg" value="String"/>
        <attribute defType="com.stambia.file.field.size" id="_smGFAYqgEe6wS8JTT7vucg" value="50"/>
      </node>
      <node defType="com.stambia.file.field" id="_smGFAoqgEe6wS8JTT7vucg" name="F13" position="13">
        <attribute defType="com.stambia.file.field.physicalName" id="_smGFA4qgEe6wS8JTT7vucg" value="F13"/>
        <attribute defType="com.stambia.file.field.type" id="_smGFBIqgEe6wS8JTT7vucg" value="String"/>
        <attribute defType="com.stambia.file.field.size" id="_smGFBYqgEe6wS8JTT7vucg" value="50"/>
      </node>
      <node defType="com.stambia.file.propertyField" id="_smGFBoqgEe6wS8JTT7vucg" name="file_name">
        <attribute defType="com.stambia.file.propertyField.property" id="_smGFB4qgEe6wS8JTT7vucg" value="file_name"/>
      </node>
    </node>
  </node>
</md:node>