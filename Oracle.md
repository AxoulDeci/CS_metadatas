<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.rdbms.server" id="_TkY50HozEe6i1bEIfNaCgQ" name="Oracle" md:ref="resource.md#UUID_MD_RDBMS_ORACLE?fileId=UUID_MD_RDBMS_ORACLE$type=md$name=Oracle?" internalVersion="v1.0.0">
  <attribute defType="com.stambia.rdbms.server.module" id="_TkjR4HozEe6i1bEIfNaCgQ" value="Oracle"/>
  <attribute defType="com.stambia.rdbms.server.user" id="_bV010HozEe6i1bEIfNaCgQ" value="CSG1_ORA1"/>
  <attribute defType="com.stambia.rdbms.server.driver" id="_bV2D8HozEe6i1bEIfNaCgQ" value="oracle.jdbc.OracleDriver"/>
  <attribute defType="com.stambia.rdbms.server.designerAutoCommit" id="_bV2D8XozEe6i1bEIfNaCgQ" value="true"/>
  <attribute defType="com.stambia.rdbms.server.password" id="_bV2rAHozEe6i1bEIfNaCgQ" value="A003F517E0B1C33FD344EACC67FAACEE"/>
  <attribute defType="com.stambia.rdbms.server.url" id="_bV2rAXozEe6i1bEIfNaCgQ" value="jdbc:oracle:thin:@195.83.93.26:1521/SIAD_PDB2"/>
  <node defType="com.stambia.rdbms.schema" id="_TpOWgHozEe6i1bEIfNaCgQ" name="CSG1_ORA1">
    <attribute defType="com.stambia.rdbms.schema.name" id="_TpzlUHozEe6i1bEIfNaCgQ" value="CSG1_ORA1"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_Tp0MYHozEe6i1bEIfNaCgQ" value="R_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_Tp0zcHozEe6i1bEIfNaCgQ" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_Tp0zcXozEe6i1bEIfNaCgQ" value="I_[targetName]"/>
    <node defType="com.stambia.rdbms.datastore" id="_bZ6EkHozEe6i1bEIfNaCgQ" name="ODS_ADRESSE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_bZ6EkXozEe6i1bEIfNaCgQ" value="ODS_ADRESSE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_bZ6EknozEe6i1bEIfNaCgQ" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_bdT94HozEe6i1bEIfNaCgQ" name="TYPE_LIGNE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_bdT94XozEe6i1bEIfNaCgQ" value="TYPE_LIGNE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bdT94nozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bdT943ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bdT95HozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bdT95XozEe6i1bEIfNaCgQ" value="3"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bdVMAHozEe6i1bEIfNaCgQ" name="ACTION" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_bdVMAXozEe6i1bEIfNaCgQ" value="ACTION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bdVMAnozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bdVMA3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bdVMBHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bdVMBXozEe6i1bEIfNaCgQ" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bdVzEHozEe6i1bEIfNaCgQ" name="CLE_CLIENT" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_bdVzEXozEe6i1bEIfNaCgQ" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bdVzEnozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bdWaIHozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bdWaIXozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bdWaInozEe6i1bEIfNaCgQ" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bdXBMHozEe6i1bEIfNaCgQ" name="STATUS" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_bdXBMXozEe6i1bEIfNaCgQ" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bdXBMnozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bdXBM3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bdXBNHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bdXBNXozEe6i1bEIfNaCgQ" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bdYPUHozEe6i1bEIfNaCgQ" name="LIGNE_1" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_bdYPUXozEe6i1bEIfNaCgQ" value="LIGNE_1"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bdYPUnozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bdYPU3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bdYPVHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bdYPVXozEe6i1bEIfNaCgQ" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bdY2YHozEe6i1bEIfNaCgQ" name="LIGNE_2" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_bdY2YXozEe6i1bEIfNaCgQ" value="LIGNE_2"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bdY2YnozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bdY2Y3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bdY2ZHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bdY2ZXozEe6i1bEIfNaCgQ" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bdaEgHozEe6i1bEIfNaCgQ" name="LIGNE_3" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_bdaEgXozEe6i1bEIfNaCgQ" value="LIGNE_3"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bdaEgnozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bdaEg3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bdaEhHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bdaEhXozEe6i1bEIfNaCgQ" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bdarkHozEe6i1bEIfNaCgQ" name="LIGNE_4" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_bdarkXozEe6i1bEIfNaCgQ" value="LIGNE_4"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bdarknozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bdark3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bdarlHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bdarlXozEe6i1bEIfNaCgQ" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bdarlnozEe6i1bEIfNaCgQ" name="LIGNE_5" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_bdarl3ozEe6i1bEIfNaCgQ" value="LIGNE_5"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bdarmHozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bdarmXozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bdarmnozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bdarm3ozEe6i1bEIfNaCgQ" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bdbSoHozEe6i1bEIfNaCgQ" name="VILLE" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_bdbSoXozEe6i1bEIfNaCgQ" value="VILLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bdbSonozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bdbSo3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bdbSpHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bdbSpXozEe6i1bEIfNaCgQ" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bdbSpnozEe6i1bEIfNaCgQ" name="CODE_POSTAL" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_bdbSp3ozEe6i1bEIfNaCgQ" value="CODE_POSTAL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bdbSqHozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bdbSqXozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bdbSqnozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bdbSq3ozEe6i1bEIfNaCgQ" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bdbSrHozEe6i1bEIfNaCgQ" name="PAYS" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_bdbSrXozEe6i1bEIfNaCgQ" value="PAYS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bdbSrnozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bdbSr3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bdbSsHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bdbSsXozEe6i1bEIfNaCgQ" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bdb5sHozEe6i1bEIfNaCgQ" name="QUALITE" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_bdb5sXozEe6i1bEIfNaCgQ" value="QUALITE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bdb5snozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bdb5s3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bdb5tHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bdb5tXozEe6i1bEIfNaCgQ" value="5"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_bkye4XozEe6i1bEIfNaCgQ" name="ODS_TELEPHONE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_bkye4nozEe6i1bEIfNaCgQ" value="ODS_TELEPHONE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_bkye43ozEe6i1bEIfNaCgQ" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_boQCkHozEe6i1bEIfNaCgQ" name="TYPE_LIGNE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_boQCkXozEe6i1bEIfNaCgQ" value="TYPE_LIGNE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_boQCknozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_boQCk3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_boQClHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_boQClXozEe6i1bEIfNaCgQ" value="3"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_boRQsHozEe6i1bEIfNaCgQ" name="ACTION" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_boRQsXozEe6i1bEIfNaCgQ" value="ACTION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_boRQsnozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_boRQs3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_boRQtHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_boRQtXozEe6i1bEIfNaCgQ" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_boSe0HozEe6i1bEIfNaCgQ" name="CLE_CLIENT" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_boSe0XozEe6i1bEIfNaCgQ" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_boSe0nozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_boSe03ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_boSe1HozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_boSe1XozEe6i1bEIfNaCgQ" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_boTF4HozEe6i1bEIfNaCgQ" name="PHONE" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_boTF4XozEe6i1bEIfNaCgQ" value="PHONE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_boTF4nozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_boTF43ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_boTF5HozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_boTF5XozEe6i1bEIfNaCgQ" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_boTs8HozEe6i1bEIfNaCgQ" name="STATUS" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_boTs8XozEe6i1bEIfNaCgQ" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_boTs8nozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_boTs83ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_boTs9HozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_boTs9XozEe6i1bEIfNaCgQ" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_boTs9nozEe6i1bEIfNaCgQ" name="FAVORI" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_boTs93ozEe6i1bEIfNaCgQ" value="FAVORI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_boTs-HozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_boTs-XozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_boTs-nozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_boTs-3ozEe6i1bEIfNaCgQ" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_boTs_HozEe6i1bEIfNaCgQ" name="TYPE" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_boTs_XozEe6i1bEIfNaCgQ" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_boTs_nozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_boTs_3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_boTtAHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_boTtAXozEe6i1bEIfNaCgQ" value="5"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_bV9YsXozEe6i1bEIfNaCgQ" name="ODS_CLIENT">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_bV9YsnozEe6i1bEIfNaCgQ" value="ODS_CLIENT"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_bV9Ys3ozEe6i1bEIfNaCgQ" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_bZyIwHozEe6i1bEIfNaCgQ" name="TYPE_LIGNE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_bZyIwXozEe6i1bEIfNaCgQ" value="TYPE_LIGNE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bZyIwnozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bZyIw3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bZyIxHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bZyIxXozEe6i1bEIfNaCgQ" value="3"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bZyv0HozEe6i1bEIfNaCgQ" name="ACTION" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_bZyv0XozEe6i1bEIfNaCgQ" value="ACTION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bZyv0nozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bZyv03ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bZyv1HozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bZyv1XozEe6i1bEIfNaCgQ" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bZyv1nozEe6i1bEIfNaCgQ" name="CLE_CLIENT" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_bZzW4HozEe6i1bEIfNaCgQ" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bZzW4XozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bZzW4nozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bZzW43ozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bZzW5HozEe6i1bEIfNaCgQ" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bZzW5XozEe6i1bEIfNaCgQ" name="CLE_COMPTE" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_bZzW5nozEe6i1bEIfNaCgQ" value="CLE_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bZzW53ozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bZzW6HozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bZzW6XozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bZzW6nozEe6i1bEIfNaCgQ" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bZzW63ozEe6i1bEIfNaCgQ" name="STATUS" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_bZzW7HozEe6i1bEIfNaCgQ" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bZzW7XozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bZzW7nozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bZzW73ozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bZzW8HozEe6i1bEIfNaCgQ" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bZzW8XozEe6i1bEIfNaCgQ" name="TYPE" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_bZzW8nozEe6i1bEIfNaCgQ" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bZzW83ozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bZzW9HozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bZzW9XozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bZzW9nozEe6i1bEIfNaCgQ" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bZzW93ozEe6i1bEIfNaCgQ" name="CIVILITE" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_bZzW-HozEe6i1bEIfNaCgQ" value="CIVILITE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bZzW-XozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bZzW-nozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bZzW-3ozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bZzW_HozEe6i1bEIfNaCgQ" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bZzW_XozEe6i1bEIfNaCgQ" name="PRENOM" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_bZzW_nozEe6i1bEIfNaCgQ" value="PRENOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bZzW_3ozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bZzXAHozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bZzXAXozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bZzXAnozEe6i1bEIfNaCgQ" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bZz98HozEe6i1bEIfNaCgQ" name="NOM" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_bZz98XozEe6i1bEIfNaCgQ" value="NOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bZz98nozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bZz983ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bZz99HozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bZz99XozEe6i1bEIfNaCgQ" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bZz99nozEe6i1bEIfNaCgQ" name="DATE_ANNIVERSAIRE" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_bZz993ozEe6i1bEIfNaCgQ" value="DATE_ANNIVERSAIRE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bZz9-HozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bZz9-XozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bZz9-nozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bZz9-3ozEe6i1bEIfNaCgQ" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bZz9_HozEe6i1bEIfNaCgQ" name="SEXE" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_bZz9_XozEe6i1bEIfNaCgQ" value="SEXE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bZz9_nozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bZz9_3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bZz-AHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bZz-AXozEe6i1bEIfNaCgQ" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bZ0lAHozEe6i1bEIfNaCgQ" name="MUTUELLE" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_bZ0lAXozEe6i1bEIfNaCgQ" value="MUTUELLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bZ0lAnozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bZ0lA3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bZ0lBHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bZ0lBXozEe6i1bEIfNaCgQ" value="5"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_bdhZQXozEe6i1bEIfNaCgQ" name="ODS_COMPTE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_bdhZQnozEe6i1bEIfNaCgQ" value="ODS_COMPTE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_bdhZQ3ozEe6i1bEIfNaCgQ" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_bgueQHozEe6i1bEIfNaCgQ" name="TYPE_LIGNE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_bgueQXozEe6i1bEIfNaCgQ" value="TYPE_LIGNE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bgueQnozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bgueQ3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bgueRHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bgueRXozEe6i1bEIfNaCgQ" value="3"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bgvFUHozEe6i1bEIfNaCgQ" name="ACTION" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_bgvFUXozEe6i1bEIfNaCgQ" value="ACTION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bgvFUnozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bgvFU3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bgvFVHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bgvFVXozEe6i1bEIfNaCgQ" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bgvFVnozEe6i1bEIfNaCgQ" name="CLE_COMPTE" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_bgvFV3ozEe6i1bEIfNaCgQ" value="CLE_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bgvFWHozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bgvFWXozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bgvFWnozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bgvFW3ozEe6i1bEIfNaCgQ" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bgvsYHozEe6i1bEIfNaCgQ" name="STATUS" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_bgvsYXozEe6i1bEIfNaCgQ" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bgvsYnozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bgvsY3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bgvsZHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bgvsZXozEe6i1bEIfNaCgQ" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bgvsZnozEe6i1bEIfNaCgQ" name="TYPE" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_bgvsZ3ozEe6i1bEIfNaCgQ" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bgvsaHozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bgvsaXozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bgvsanozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bgvsa3ozEe6i1bEIfNaCgQ" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bgvsbHozEe6i1bEIfNaCgQ" name="CABINET_RATTACHEMENT" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_bgvsbXozEe6i1bEIfNaCgQ" value="CABINET_RATTACHEMENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bgvsbnozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bgvsb3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bgvscHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bgvscXozEe6i1bEIfNaCgQ" value="9"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_bg0k4XozEe6i1bEIfNaCgQ" name="ODS_EMAIL">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_bg0k4nozEe6i1bEIfNaCgQ" value="ODS_EMAIL"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_bg0k43ozEe6i1bEIfNaCgQ" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_bkpU8HozEe6i1bEIfNaCgQ" name="TYPE_LIGNE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_bkpU8XozEe6i1bEIfNaCgQ" value="TYPE_LIGNE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bkpU8nozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bkpU83ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bkpU9HozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bkpU9XozEe6i1bEIfNaCgQ" value="3"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bkqjEHozEe6i1bEIfNaCgQ" name="ACTION" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_bkqjEXozEe6i1bEIfNaCgQ" value="ACTION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bkqjEnozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bkqjE3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bkqjFHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bkqjFXozEe6i1bEIfNaCgQ" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bkrxMHozEe6i1bEIfNaCgQ" name="CLE_CLIENT" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_bkrxMXozEe6i1bEIfNaCgQ" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bkrxMnozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bkrxM3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bkrxNHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bkrxNXozEe6i1bEIfNaCgQ" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bksYQHozEe6i1bEIfNaCgQ" name="EMAIL" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_bksYQXozEe6i1bEIfNaCgQ" value="EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bksYQnozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bksYQ3ozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bksYRHozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bksYRXozEe6i1bEIfNaCgQ" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bksYRnozEe6i1bEIfNaCgQ" name="STATUS" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_bksYR3ozEe6i1bEIfNaCgQ" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bksYSHozEe6i1bEIfNaCgQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bksYSXozEe6i1bEIfNaCgQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bksYSnozEe6i1bEIfNaCgQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bksYS3ozEe6i1bEIfNaCgQ" value="5"/>
      </node>
    </node>
  </node>
</md:node>