<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.rdbms.server" id="_TkY50HozEe6i1bEIfNaCgQ" name="Oracle" md:ref="resource.md#UUID_MD_RDBMS_ORACLE?fileId=UUID_MD_RDBMS_ORACLE$type=md$name=Oracle?" internalVersion="v1.0.0">
  <attribute defType="com.stambia.rdbms.server.module" id="_TkjR4HozEe6i1bEIfNaCgQ" value="Oracle"/>
  <attribute defType="com.stambia.rdbms.server.user" id="_bV010HozEe6i1bEIfNaCgQ" value="CSG1_ORA1"/>
  <attribute defType="com.stambia.rdbms.server.driver" id="_bV2D8HozEe6i1bEIfNaCgQ" value="oracle.jdbc.OracleDriver"/>
  <attribute defType="com.stambia.rdbms.server.designerAutoCommit" id="_bV2D8XozEe6i1bEIfNaCgQ" value="true"/>
  <attribute defType="com.stambia.rdbms.server.password" id="_bV2rAHozEe6i1bEIfNaCgQ" value="A003F517E0B1C33FD344EACC67FAACEE"/>
  <attribute defType="com.stambia.rdbms.server.url" id="_bV2rAXozEe6i1bEIfNaCgQ" value="jdbc:oracle:thin:@195.83.93.26:1521/SIAD_PDB2"/>
  <node defType="com.stambia.rdbms.schema" id="_TpOWgHozEe6i1bEIfNaCgQ" name="ODS">
    <attribute defType="com.stambia.rdbms.schema.name" id="_TpzlUHozEe6i1bEIfNaCgQ" value="CSG1_ORA1"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_Tp0MYHozEe6i1bEIfNaCgQ" value="R_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_Tp0zcHozEe6i1bEIfNaCgQ" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_Tp0zcXozEe6i1bEIfNaCgQ" value="I_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.dataStoreFilter" id="_HAl1EH-kEe6JNIokCBopZg" value="ODS%"/>
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
      <node defType="com.stambia.rdbms.column" id="_G0IGZn-kEe6JNIokCBopZg" name="DATE_CREATION" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_G0IGZ3-kEe6JNIokCBopZg" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_G0IGaH-kEe6JNIokCBopZg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_G0IGaX-kEe6JNIokCBopZg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_G0IGan-kEe6JNIokCBopZg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_G0IGa3-kEe6JNIokCBopZg" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_G0ItcH-kEe6JNIokCBopZg" name="ID_FICHIER" position="15">
        <attribute defType="com.stambia.rdbms.column.name" id="_G0ItcX-kEe6JNIokCBopZg" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_G0Itcn-kEe6JNIokCBopZg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_G0Itc3-kEe6JNIokCBopZg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_G0ItdH-kEe6JNIokCBopZg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_G0ItdX-kEe6JNIokCBopZg" value="20"/>
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
      <node defType="com.stambia.rdbms.column" id="_G_qoBn-kEe6JNIokCBopZg" name="DATE_CREATION" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_G_qoB3-kEe6JNIokCBopZg" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_G_qoCH-kEe6JNIokCBopZg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_G_qoCX-kEe6JNIokCBopZg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_G_qoCn-kEe6JNIokCBopZg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_G_qoC3-kEe6JNIokCBopZg" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_G_rPEH-kEe6JNIokCBopZg" name="ID_FICHIER" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_G_rPEX-kEe6JNIokCBopZg" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_G_rPEn-kEe6JNIokCBopZg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_G_rPE3-kEe6JNIokCBopZg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_G_rPFH-kEe6JNIokCBopZg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_G_rPFX-kEe6JNIokCBopZg" value="20"/>
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
      <node defType="com.stambia.rdbms.column" id="_GwVyln-kEe6JNIokCBopZg" name="DATE_CREATION" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_GwVyl3-kEe6JNIokCBopZg" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_GwVymH-kEe6JNIokCBopZg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_GwVymX-kEe6JNIokCBopZg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_GwVymn-kEe6JNIokCBopZg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_GwVym3-kEe6JNIokCBopZg" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_GwVynH-kEe6JNIokCBopZg" name="ID_FICHIER" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_GwVynX-kEe6JNIokCBopZg" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_GwVynn-kEe6JNIokCBopZg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_GwVyn3-kEe6JNIokCBopZg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_GwVyoH-kEe6JNIokCBopZg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_GwVyoX-kEe6JNIokCBopZg" value="20"/>
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
      <node defType="com.stambia.rdbms.column" id="_G4MHAH-kEe6JNIokCBopZg" name="DATE_CREATION" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_G4MHAX-kEe6JNIokCBopZg" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_G4MHAn-kEe6JNIokCBopZg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_G4MHA3-kEe6JNIokCBopZg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_G4MHBH-kEe6JNIokCBopZg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_G4MHBX-kEe6JNIokCBopZg" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_G4MHBn-kEe6JNIokCBopZg" name="ID_FICHIER" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_G4MHB3-kEe6JNIokCBopZg" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_G4MHCH-kEe6JNIokCBopZg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_G4MHCX-kEe6JNIokCBopZg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_G4MHCn-kEe6JNIokCBopZg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_G4MHC3-kEe6JNIokCBopZg" value="20"/>
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
      <node defType="com.stambia.rdbms.column" id="_G747QH-kEe6JNIokCBopZg" name="DATE_CREATION" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_G747QX-kEe6JNIokCBopZg" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_G747Qn-kEe6JNIokCBopZg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_G747Q3-kEe6JNIokCBopZg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_G747RH-kEe6JNIokCBopZg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_G747RX-kEe6JNIokCBopZg" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_G75iUH-kEe6JNIokCBopZg" name="ID_FICHIER" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_G75iUX-kEe6JNIokCBopZg" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_G75iUn-kEe6JNIokCBopZg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_G76JYH-kEe6JNIokCBopZg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_G76JYX-kEe6JNIokCBopZg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_G76JYn-kEe6JNIokCBopZg" value="20"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_Yc_LwX-qEe6IE6AcCtnNjw" name="ODS_PIED">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_Yc_Lwn-qEe6IE6AcCtnNjw" value="ODS_PIED"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_Yc_Lw3-qEe6IE6AcCtnNjw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_YgekoH-qEe6IE6AcCtnNjw" name="TYPE_LIGNE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_YgekoX-qEe6IE6AcCtnNjw" value="TYPE_LIGNE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Ygekon-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Ygeko3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_YgekpH-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_YgekpX-qEe6IE6AcCtnNjw" value="3"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Ygekpn-qEe6IE6AcCtnNjw" name="NB_LIGNE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_Ygekp3-qEe6IE6AcCtnNjw" value="NB_LIGNE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_YgekqH-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_YgekqX-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Ygekqn-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Ygekq3-qEe6IE6AcCtnNjw" value="10"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_YNcT4X-qEe6IE6AcCtnNjw" name="ODS_ENTETE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_YNcT4n-qEe6IE6AcCtnNjw" value="ODS_ENTETE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_YNcT43-qEe6IE6AcCtnNjw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_YRqFgH-qEe6IE6AcCtnNjw" name="TYPE_LIGNE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_YRqFgX-qEe6IE6AcCtnNjw" value="TYPE_LIGNE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_YRqFgn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_YRqFg3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_YRqFhH-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_YRqFhX-qEe6IE6AcCtnNjw" value="3"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_YRqskH-qEe6IE6AcCtnNjw" name="TYPE_FICHIER" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_YRrToH-qEe6IE6AcCtnNjw" value="TYPE_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_YRrToX-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_YRrTon-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_YRrTo3-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_YRrTpH-qEe6IE6AcCtnNjw" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_YRr6sH-qEe6IE6AcCtnNjw" name="VERSION" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_YRr6sX-qEe6IE6AcCtnNjw" value="VERSION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_YRr6sn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_YRr6s3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_YRr6tH-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_YRr6tX-qEe6IE6AcCtnNjw" value="2"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_YRshwH-qEe6IE6AcCtnNjw" name="DATE_ENTETE" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_YRshwX-qEe6IE6AcCtnNjw" value="DATE_ENTETE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_YRshwn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_YRshw3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_YRshxH-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_YRshxX-qEe6IE6AcCtnNjw" value="30"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_YRtI0H-qEe6IE6AcCtnNjw" name="SOURCE" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_YRtI0X-qEe6IE6AcCtnNjw" value="SOURCE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_YRtI0n-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_YRtI03-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_YRtI1H-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_YRtI1X-qEe6IE6AcCtnNjw" value="30"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_YRtI1n-qEe6IE6AcCtnNjw" name="SEQUENCE" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_YRtI13-qEe6IE6AcCtnNjw" value="SEQUENCE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_YRtI2H-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_YRtI2X-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_YRtI2n-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_YRtI23-qEe6IE6AcCtnNjw" value="8"/>
      </node>
    </node>
  </node>
  <node defType="com.stambia.rdbms.schema" id="_2GWSwH-pEe6IE6AcCtnNjw" name="DWH">
    <attribute defType="com.stambia.rdbms.schema.name" id="_6hS0EH-pEe6IE6AcCtnNjw" value="CSG1_ORA1"/>
    <attribute defType="com.stambia.rdbms.schema.dataStoreFilter" id="_-K5YAH-pEe6IE6AcCtnNjw" value="DWH%"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_6U9XEIUhEe6ELc6b5-F_4A" value="R_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_6VCPkIUhEe6ELc6b5-F_4A" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_6VC2oIUhEe6ELc6b5-F_4A" value="I_[targetName]"/>
    <node defType="com.stambia.rdbms.datastore" id="_QfSVYX-qEe6IE6AcCtnNjw" name="DWH_EMAIL">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_QfSVYn-qEe6IE6AcCtnNjw" value="DWH_EMAIL"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_QfSVY3-qEe6IE6AcCtnNjw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_QkgMkH-qEe6IE6AcCtnNjw" name="SID_CLI" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkgMkX-qEe6IE6AcCtnNjw" value="SID_CLI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkgMkn-qEe6IE6AcCtnNjw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkgMk3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkgMlH-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkgMlX-qEe6IE6AcCtnNjw" value="10"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_GmhCgIq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkhasH-qEe6IE6AcCtnNjw" name="EMAIL" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkhasX-qEe6IE6AcCtnNjw" value="EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qkhasn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qkhas3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkhatH-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkhatX-qEe6IE6AcCtnNjw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiBwH-qEe6IE6AcCtnNjw" name="STATUS_EMAIL" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiBwX-qEe6IE6AcCtnNjw" value="STATUS_EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiBwn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiBw3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiBxH-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiBxX-qEe6IE6AcCtnNjw" value="5"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_GmhCgYq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkkeAH-qEe6IE6AcCtnNjw" name="ID_FICHIER" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkkeAX-qEe6IE6AcCtnNjw" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkkeAn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkkeA3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkkeBH-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkkeBX-qEe6IE6AcCtnNjw" value="10"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_GmhCgoq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QklsIH-qEe6IE6AcCtnNjw" name="DERNIERE_DATE_MAJ_EMAIL" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_QklsIX-qEe6IE6AcCtnNjw" value="DERNIERE_DATE_MAJ_EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QklsIn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QklsI3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QklsJH-qEe6IE6AcCtnNjw" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QklsJX-qEe6IE6AcCtnNjw" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkmTMH-qEe6IE6AcCtnNjw" name="DATE_CREATION_EMAIL" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkmTMX-qEe6IE6AcCtnNjw" value="DATE_CREATION_EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkmTMn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkmTM3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkmTNH-qEe6IE6AcCtnNjw" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkmTNX-qEe6IE6AcCtnNjw" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_Qkp9kH-qEe6IE6AcCtnNjw" name="DWH_EMAIL_PK">
        <node defType="com.stambia.rdbms.colref" id="_Qkp9kX-qEe6IE6AcCtnNjw" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_Qkp9kn-qEe6IE6AcCtnNjw" ref="resource.md#_QkgMkH-qEe6IE6AcCtnNjw?fileId=_TkY50HozEe6i1bEIfNaCgQ$type=md$name=SID_CLI?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bXaLdoqgEe6Bpuf23-D2iA" name="RECORD_VERSION" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_bXaLd4qgEe6Bpuf23-D2iA" value="RECORD_VERSION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bXaLeIqgEe6Bpuf23-D2iA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bXaLeYqgEe6Bpuf23-D2iA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bXaLeoqgEe6Bpuf23-D2iA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bXaLe4qgEe6Bpuf23-D2iA" value="2"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_QZvHAX-qEe6IE6AcCtnNjw" name="DWH_ADRESSE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_QZvHAn-qEe6IE6AcCtnNjw" value="DWH_ADRESSE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_QZvHA3-qEe6IE6AcCtnNjw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_QfFhEH-qEe6IE6AcCtnNjw" name="SID_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_QfFhEX-qEe6IE6AcCtnNjw" value="SID_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QfFhEn-qEe6IE6AcCtnNjw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QfFhE3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QfFhFH-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QfFhFX-qEe6IE6AcCtnNjw" value="10"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_GmX4kIq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QfGIIH-qEe6IE6AcCtnNjw" name="STATUS_ADR" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_QfGIIX-qEe6IE6AcCtnNjw" value="STATUS_ADR"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QfGIIn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QfGII3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QfGIJH-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QfGIJX-qEe6IE6AcCtnNjw" value="10"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_GmYfoIq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QfGvMH-qEe6IE6AcCtnNjw" name="NUMERO_ADR" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_QfGvMX-qEe6IE6AcCtnNjw" value="NUMERO_ADR"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QfGvMn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QfGvM3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QfGvNH-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QfGvNX-qEe6IE6AcCtnNjw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QfGvNn-qEe6IE6AcCtnNjw" name="RUE_ADR" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_QfGvN3-qEe6IE6AcCtnNjw" value="RUE_ADR"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QfGvOH-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QfGvOX-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QfGvOn-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QfGvO3-qEe6IE6AcCtnNjw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QfHWQH-qEe6IE6AcCtnNjw" name="CPM_ADR_1" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_QfHWQX-qEe6IE6AcCtnNjw" value="CPM_ADR_1"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QfHWQn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QfHWQ3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QfHWRH-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QfHWRX-qEe6IE6AcCtnNjw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QfH9UH-qEe6IE6AcCtnNjw" name="CPM_ADR_2" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_QfH9UX-qEe6IE6AcCtnNjw" value="CPM_ADR_2"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QfH9Un-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QfH9U3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QfH9VH-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QfH9VX-qEe6IE6AcCtnNjw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QfH9Vn-qEe6IE6AcCtnNjw" name="CPM_ADR_3" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_QfH9V3-qEe6IE6AcCtnNjw" value="CPM_ADR_3"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QfH9WH-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QfH9WX-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QfH9Wn-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QfH9W3-qEe6IE6AcCtnNjw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QfIkYH-qEe6IE6AcCtnNjw" name="VILLE_ADR" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_QfIkYX-qEe6IE6AcCtnNjw" value="VILLE_ADR"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QfIkYn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QfIkY3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QfIkZH-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QfIkZX-qEe6IE6AcCtnNjw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QfIkZn-qEe6IE6AcCtnNjw" name="CODE_POSTAL_ADR" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_QfIkZ3-qEe6IE6AcCtnNjw" value="CODE_POSTAL_ADR"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QfIkaH-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QfIkaX-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QfIkan-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QfIka3-qEe6IE6AcCtnNjw" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QfJLcH-qEe6IE6AcCtnNjw" name="PAYS_ADR" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_QfJLcX-qEe6IE6AcCtnNjw" value="PAYS_ADR"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QfJLcn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QfJLc3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QfJLdH-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QfJLdX-qEe6IE6AcCtnNjw" value="10"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_GmYfoYq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QfJygH-qEe6IE6AcCtnNjw" name="LIB_PAYS_ADR" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_QfJygX-qEe6IE6AcCtnNjw" value="LIB_PAYS_ADR"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QfJygn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QfJyg3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QfJyhH-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QfJyhX-qEe6IE6AcCtnNjw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QfJyhn-qEe6IE6AcCtnNjw" name="QUALITE_ADR" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_QfJyh3-qEe6IE6AcCtnNjw" value="QUALITE_ADR"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QfJyiH-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QfJyiX-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QfJyin-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QfJyi3-qEe6IE6AcCtnNjw" value="10"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_GmYfooq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QfLAoH-qEe6IE6AcCtnNjw" name="ID_FICHIER" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_QfLAoX-qEe6IE6AcCtnNjw" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QfLAon-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QfLAo3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QfLApH-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QfLApX-qEe6IE6AcCtnNjw" value="10"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_GmZGsIq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QfLApn-qEe6IE6AcCtnNjw" name="DATE_DERNIERE_MAJ_ADR" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_QfLAp3-qEe6IE6AcCtnNjw" value="DATE_DERNIERE_MAJ_ADR"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QfLAqH-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QfLAqX-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QfLAqn-qEe6IE6AcCtnNjw" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QfLAq3-qEe6IE6AcCtnNjw" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QfLnsH-qEe6IE6AcCtnNjw" name="DATE_CREATION_ADR" position="15">
        <attribute defType="com.stambia.rdbms.column.name" id="_QfLnsX-qEe6IE6AcCtnNjw" value="DATE_CREATION_ADR"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QfLnsn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QfLns3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QfLntH-qEe6IE6AcCtnNjw" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QfLntX-qEe6IE6AcCtnNjw" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_QfPSEH-qEe6IE6AcCtnNjw" name="DWH_ADRESSE_PK">
        <node defType="com.stambia.rdbms.colref" id="_QfPSEX-qEe6IE6AcCtnNjw" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_QfPSEn-qEe6IE6AcCtnNjw" ref="resource.md#_QfFhEH-qEe6IE6AcCtnNjw?fileId=_TkY50HozEe6i1bEIfNaCgQ$type=md$name=SID_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bRd7hoqgEe6Bpuf23-D2iA" name="RECORD_VERSION" position="16">
        <attribute defType="com.stambia.rdbms.column.name" id="_bRd7h4qgEe6Bpuf23-D2iA" value="RECORD_VERSION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bRd7iIqgEe6Bpuf23-D2iA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bRd7iYqgEe6Bpuf23-D2iA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bRd7ioqgEe6Bpuf23-D2iA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bRd7i4qgEe6Bpuf23-D2iA" value="2"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_QksZ0X-qEe6IE6AcCtnNjw" name="DWH_CLIENT">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_QksZ0n-qEe6IE6AcCtnNjw" value="DWH_CLIENT"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_QksZ03-qEe6IE6AcCtnNjw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_Qqs7MH-qEe6IE6AcCtnNjw" name="SID_CLI" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qqs7MX-qEe6IE6AcCtnNjw" value="SID_CLI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qqs7Mn-qEe6IE6AcCtnNjw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qqs7M3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qqs7NH-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QqtiQH-qEe6IE6AcCtnNjw" value="10"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_GmemQIq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QquJUH-qEe6IE6AcCtnNjw" name="CLE_CLI" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_QquJUX-qEe6IE6AcCtnNjw" value="CLE_CLI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QquJUn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QquJU3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QquJVH-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QquJVX-qEe6IE6AcCtnNjw" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QquJVn-qEe6IE6AcCtnNjw" name="SID_CPT" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_QquJV3-qEe6IE6AcCtnNjw" value="SID_CPT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QquJWH-qEe6IE6AcCtnNjw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QquJWX-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QquJWn-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QquJW3-qEe6IE6AcCtnNjw" value="10"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_GmemQYq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QquwYH-qEe6IE6AcCtnNjw" name="STATUS_CLI" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_QquwYX-qEe6IE6AcCtnNjw" value="STATUS_CLI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QquwYn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QquwY3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QquwZH-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QquwZX-qEe6IE6AcCtnNjw" value="5"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_GmemQoq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QqvXcH-qEe6IE6AcCtnNjw" name="TYPE_CLI" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_QqvXcX-qEe6IE6AcCtnNjw" value="TYPE_CLI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QqvXcn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QqvXc3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QqvXdH-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QqvXdX-qEe6IE6AcCtnNjw" value="5"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_GmemQ4q4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QqvXdn-qEe6IE6AcCtnNjw" name="CIVILITE_CLI" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_QqvXd3-qEe6IE6AcCtnNjw" value="CIVILITE_CLI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QqvXeH-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QqvXeX-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QqvXen-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QqvXe3-qEe6IE6AcCtnNjw" value="5"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_GmemRIq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Qqv-gH-qEe6IE6AcCtnNjw" name="PRENOM_CLI" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qqv-gX-qEe6IE6AcCtnNjw" value="PRENOM_CLI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qqv-gn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qqv-g3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qqv-hH-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Qqv-hX-qEe6IE6AcCtnNjw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QqwlkH-qEe6IE6AcCtnNjw" name="NOM_CLI" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_QqwlkX-qEe6IE6AcCtnNjw" value="NOM_CLI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qqwlkn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qqwlk3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QqwllH-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QqwllX-qEe6IE6AcCtnNjw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QqxMoH-qEe6IE6AcCtnNjw" name="DATE_ANNV_CLI" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_QqxMoX-qEe6IE6AcCtnNjw" value="DATE_ANNV_CLI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QqxMon-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QqxMo3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QqxMpH-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QqxMpX-qEe6IE6AcCtnNjw" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QqxMpn-qEe6IE6AcCtnNjw" name="SEXE_CLI" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_QqxMp3-qEe6IE6AcCtnNjw" value="SEXE_CLI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QqxMqH-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QqxMqX-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QqxMqn-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QqxMq3-qEe6IE6AcCtnNjw" value="5"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_GmemRYq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QqxzsH-qEe6IE6AcCtnNjw" name="MUTUELLE_CLI" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_QqxzsX-qEe6IE6AcCtnNjw" value="MUTUELLE_CLI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qqxzsn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qqxzs3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QqxztH-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QqxztX-qEe6IE6AcCtnNjw" value="5"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_GmemRoq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Qqyaxn-qEe6IE6AcCtnNjw" name="LIB_SEXE_CLI" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qqyax3-qEe6IE6AcCtnNjw" value="LIB_SEXE_CLI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QqyayH-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QqyayX-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qqyayn-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Qqyay3-qEe6IE6AcCtnNjw" value="15"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QqzB0H-qEe6IE6AcCtnNjw" name="LIB_TYPE_CLI" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_QqzB0X-qEe6IE6AcCtnNjw" value="LIB_TYPE_CLI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QqzB0n-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QqzB03-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QqzB1H-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QqzB1X-qEe6IE6AcCtnNjw" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QqzB1n-qEe6IE6AcCtnNjw" name="LIB_CIVILITE_CLI" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_QqzB13-qEe6IE6AcCtnNjw" value="LIB_CIVILITE_CLI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QqzB2H-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QqzB2X-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QqzB2n-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QqzB23-qEe6IE6AcCtnNjw" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Qqzo4H-qEe6IE6AcCtnNjw" name="ID_FICHIER" position="15">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qqzo4X-qEe6IE6AcCtnNjw" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qqzo4n-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qqzo43-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qqzo5H-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Qqzo5X-qEe6IE6AcCtnNjw" value="10"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_GmemR4q4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Qqzo5n-qEe6IE6AcCtnNjw" name="DERNIERE_DATE_MAJ_CLI" position="16">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qqzo53-qEe6IE6AcCtnNjw" value="DERNIERE_DATE_MAJ_CLI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qqzo6H-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qqzo6X-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qqzo6n-qEe6IE6AcCtnNjw" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Qqzo63-qEe6IE6AcCtnNjw" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Qqzo7H-qEe6IE6AcCtnNjw" name="DATE_CREATION_CLI" position="17">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qqzo7X-qEe6IE6AcCtnNjw" value="DATE_CREATION_CLI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qqzo7n-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qqzo73-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qqzo8H-qEe6IE6AcCtnNjw" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Qqzo8X-qEe6IE6AcCtnNjw" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_Qq2sMH-qEe6IE6AcCtnNjw" name="DWH_CLIENT_PK">
        <node defType="com.stambia.rdbms.colref" id="_Qq2sMX-qEe6IE6AcCtnNjw" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_Qq2sMn-qEe6IE6AcCtnNjw" ref="resource.md#_Qqs7MH-qEe6IE6AcCtnNjw?fileId=_TkY50HozEe6i1bEIfNaCgQ$type=md$name=SID_CLI?"/>
        </node>
        <node defType="com.stambia.rdbms.colref" id="_Qq3TQH-qEe6IE6AcCtnNjw" position="2">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_Qq3TQX-qEe6IE6AcCtnNjw" ref="resource.md#_QquJVn-qEe6IE6AcCtnNjw?fileId=_TkY50HozEe6i1bEIfNaCgQ$type=md$name=SID_CPT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bc8yxoqgEe6Bpuf23-D2iA" name="RECORD_VERSION" position="18">
        <attribute defType="com.stambia.rdbms.column.name" id="_bc8yx4qgEe6Bpuf23-D2iA" value="RECORD_VERSION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bc8yyIqgEe6Bpuf23-D2iA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bc8yyYqgEe6Bpuf23-D2iA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bc8yyoqgEe6Bpuf23-D2iA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bc8yy4qgEe6Bpuf23-D2iA" value="2"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_QUCHoX-qEe6IE6AcCtnNjw" name="DWH_COMPTE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_QUCHon-qEe6IE6AcCtnNjw" value="DWH_COMPTE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_QUCHo3-qEe6IE6AcCtnNjw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_QZoZUH-qEe6IE6AcCtnNjw" name="SID_CPT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_QZoZUX-qEe6IE6AcCtnNjw" value="SID_CPT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QZoZUn-qEe6IE6AcCtnNjw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QZoZU3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QZoZVH-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QZoZVX-qEe6IE6AcCtnNjw" value="10"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_Gma74Iq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QZpAYH-qEe6IE6AcCtnNjw" name="CLE_CPT" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_QZpAYX-qEe6IE6AcCtnNjw" value="CLE_CPT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QZpAYn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QZpAY3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QZpAZH-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QZpAZX-qEe6IE6AcCtnNjw" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QZpAZn-qEe6IE6AcCtnNjw" name="TYPE_CPT" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_QZpAZ3-qEe6IE6AcCtnNjw" value="TYPE_CPT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QZpAaH-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QZpAaX-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QZpAan-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QZpAa3-qEe6IE6AcCtnNjw" value="5"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_Gma74Yq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QZpAbH-qEe6IE6AcCtnNjw" name="LIB_TYPE_CPT" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_QZpAbX-qEe6IE6AcCtnNjw" value="LIB_TYPE_CPT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QZpAbn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QZpAb3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QZpAcH-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QZpAcX-qEe6IE6AcCtnNjw" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QZpncH-qEe6IE6AcCtnNjw" name="STATUS_CPT" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_QZpncX-qEe6IE6AcCtnNjw" value="STATUS_CPT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QZpncn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QZpnc3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QZpndH-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QZpndX-qEe6IE6AcCtnNjw" value="5"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_Gma74oq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QZpnfH-qEe6IE6AcCtnNjw" name="CABINET_RATTACHEMENT" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_QZpnfX-qEe6IE6AcCtnNjw" value="CABINET_RATTACHEMENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QZpnfn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QZpnf3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QZpngH-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QZpngX-qEe6IE6AcCtnNjw" value="9"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_Gma744q4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QZpngn-qEe6IE6AcCtnNjw" name="ID_FICHIER" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_QZpng3-qEe6IE6AcCtnNjw" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QZpnhH-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QZpnhX-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QZpnhn-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QZpnh3-qEe6IE6AcCtnNjw" value="5"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_Gma75Iq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QZqOgH-qEe6IE6AcCtnNjw" name="DERNIERE_DATE_MAJ_CPT" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_QZqOgX-qEe6IE6AcCtnNjw" value="DERNIERE_DATE_MAJ_CPT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QZqOgn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QZqOg3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QZqOhH-qEe6IE6AcCtnNjw" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QZqOhX-qEe6IE6AcCtnNjw" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QZqOhn-qEe6IE6AcCtnNjw" name="DATE_CREATION_CPT" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_QZqOh3-qEe6IE6AcCtnNjw" value="DATE_CREATION_CPT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QZqOiH-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QZqOiX-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QZqOin-qEe6IE6AcCtnNjw" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QZqOi3-qEe6IE6AcCtnNjw" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QZqOjH-qEe6IE6AcCtnNjw" name="LIB_CABINET_CPT" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_QZqOjX-qEe6IE6AcCtnNjw" value="LIB_CABINET_CPT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QZqOjn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QZqOj3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QZqOkH-qEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QZqOkX-qEe6IE6AcCtnNjw" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_QZtR0H-qEe6IE6AcCtnNjw" name="DWH_COMPTE_PK">
        <node defType="com.stambia.rdbms.colref" id="_QZtR0X-qEe6IE6AcCtnNjw" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_QZtR0n-qEe6IE6AcCtnNjw" ref="resource.md#_QZoZUH-qEe6IE6AcCtnNjw?fileId=_TkY50HozEe6i1bEIfNaCgQ$type=md$name=SID_CPT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.column" id="_a8bfpoqgEe6Bpuf23-D2iA" name="RECORD_VERSION" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_a8bfp4qgEe6Bpuf23-D2iA" value="RECORD_VERSION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_a8bfqIqgEe6Bpuf23-D2iA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_a8bfqYqgEe6Bpuf23-D2iA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_a8bfqoqgEe6Bpuf23-D2iA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_a8bfq4qgEe6Bpuf23-D2iA" value="2"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_Qq5IcX-qEe6IE6AcCtnNjw" name="DWH_TELEPHONE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_Qq5Icn-qEe6IE6AcCtnNjw" value="DWH_TELEPHONE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_Qq5Ic3-qEe6IE6AcCtnNjw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_QwJb4H-qEe6IE6AcCtnNjw" name="SID_CLI" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_QwJb4X-qEe6IE6AcCtnNjw" value="SID_CLI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QwJb4n-qEe6IE6AcCtnNjw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QwJb43-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QwJb5H-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QwJb5X-qEe6IE6AcCtnNjw" value="10"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_Gmf0YIq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QwKqAH-qEe6IE6AcCtnNjw" name="TYPE_TEL" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_QwKqAX-qEe6IE6AcCtnNjw" value="TYPE_TEL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QwKqAn-qEe6IE6AcCtnNjw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QwKqA3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QwKqBH-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QwKqBX-qEe6IE6AcCtnNjw" value="5"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_Gmf0YYq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QwLREH-qEe6IE6AcCtnNjw" name="NUM_TEL" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_QwLREX-qEe6IE6AcCtnNjw" value="NUM_TEL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QwLREn-qEe6IE6AcCtnNjw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QwLRE3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QwLRFH-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QwLRFX-qEe6IE6AcCtnNjw" value="38"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_Gmf0Yoq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QwL4IH-qEe6IE6AcCtnNjw" name="STATUS_TEL" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_QwL4IX-qEe6IE6AcCtnNjw" value="STATUS_TEL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QwL4In-qEe6IE6AcCtnNjw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QwL4I3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QwL4JH-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QwL4JX-qEe6IE6AcCtnNjw" value="5"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_Gmf0Y4q4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QwMfMH-qEe6IE6AcCtnNjw" name="FAVORI_TEL" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_QwNGQH-qEe6IE6AcCtnNjw" value="FAVORI_TEL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QwNGQX-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QwNGQn-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QwNGQ3-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QwNGRH-qEe6IE6AcCtnNjw" value="5"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_Gmf0ZIq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QwPigH-qEe6IE6AcCtnNjw" name="ID_FICHIER" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_QwPigX-qEe6IE6AcCtnNjw" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QwPign-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QwPig3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QwPihH-qEe6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QwPihX-qEe6IE6AcCtnNjw" value="5"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_GmgbcIq4Ee6iRfqSgb1Pvw" value="0"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QwQJkH-qEe6IE6AcCtnNjw" name="DERNIERE_DATE_MAJ_TEL" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_QwQJkX-qEe6IE6AcCtnNjw" value="DERNIERE_DATE_MAJ_TEL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QwQJkn-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QwQJk3-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QwQJlH-qEe6IE6AcCtnNjw" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QwQJlX-qEe6IE6AcCtnNjw" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QwQJln-qEe6IE6AcCtnNjw" name="DATE_CREATION_TEL" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_QwQJl3-qEe6IE6AcCtnNjw" value="DATE_CREATION_TEL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QwQJmH-qEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QwQJmX-qEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QwQJmn-qEe6IE6AcCtnNjw" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QwQJm3-qEe6IE6AcCtnNjw" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_QwTz8H-qEe6IE6AcCtnNjw" name="DWH_TELEPHONE_PK">
        <node defType="com.stambia.rdbms.colref" id="_QwTz8X-qEe6IE6AcCtnNjw" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_QwTz8n-qEe6IE6AcCtnNjw" ref="resource.md#_QwJb4H-qEe6IE6AcCtnNjw?fileId=_TkY50HozEe6i1bEIfNaCgQ$type=md$name=SID_CLI?"/>
        </node>
        <node defType="com.stambia.rdbms.colref" id="_QwTz83-qEe6IE6AcCtnNjw" position="2">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_QwTz9H-qEe6IE6AcCtnNjw" ref="resource.md#_QwKqAH-qEe6IE6AcCtnNjw?fileId=_TkY50HozEe6i1bEIfNaCgQ$type=md$name=TYPE_TEL?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RCsq0H-yEe6IE6AcCtnNjw" name="LIB_TYPE_TEL" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_RCsq0X-yEe6IE6AcCtnNjw" value="LIB_TYPE_TEL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RCsq0n-yEe6IE6AcCtnNjw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RCsq03-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RCsq1H-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RCsq1X-yEe6IE6AcCtnNjw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_biidZoqgEe6Bpuf23-D2iA" name="RECORD_VERSION" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_biidZ4qgEe6Bpuf23-D2iA" value="RECORD_VERSION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_biidaIqgEe6Bpuf23-D2iA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_biidaYqgEe6Bpuf23-D2iA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_biidaoqgEe6Bpuf23-D2iA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_biida4qgEe6Bpuf23-D2iA" value="2"/>
      </node>
    </node>
  </node>
  <node defType="com.stambia.rdbms.schema" id="_AHwtUH-qEe6IE6AcCtnNjw" name="SAS">
    <attribute defType="com.stambia.rdbms.schema.name" id="_A-HtkH-qEe6IE6AcCtnNjw" value="CSG1_ORA1"/>
    <attribute defType="com.stambia.rdbms.schema.dataStoreFilter" id="_O0WdkH-qEe6IE6AcCtnNjw" value="SAS%"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_BjJ2kIU3Ee6kybSjKPTayw" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_CKmREIU3Ee6kybSjKPTayw" value="I_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_EFlXEIU3Ee6kybSjKPTayw" value="R_[targetName]"/>
    <node defType="com.stambia.rdbms.datastore" id="_HqKOIX-yEe6IE6AcCtnNjw" name="SAS_EMAIL">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_HqKOIn-yEe6IE6AcCtnNjw" value="SAS_EMAIL"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_HqKOI3-yEe6IE6AcCtnNjw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_HtvGkH-yEe6IE6AcCtnNjw" name="TYPE_LIGNE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_HtvGkX-yEe6IE6AcCtnNjw" value="TYPE_LIGNE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HtvGkn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HtvGk3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HtvGlH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HtvGlX-yEe6IE6AcCtnNjw" value="3"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HtvtoH-yEe6IE6AcCtnNjw" name="ACTION" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_HtvtoX-yEe6IE6AcCtnNjw" value="ACTION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Htvton-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Htvto3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HtvtpH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HtvtpX-yEe6IE6AcCtnNjw" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Htw7wH-yEe6IE6AcCtnNjw" name="CLE_CLIENT" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_Htw7wX-yEe6IE6AcCtnNjw" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Htw7wn-yEe6IE6AcCtnNjw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Htw7w3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Htw7xH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Htw7xX-yEe6IE6AcCtnNjw" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Htxi0H-yEe6IE6AcCtnNjw" name="EMAIL" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_Htxi0X-yEe6IE6AcCtnNjw" value="EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Htxi0n-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Htxi03-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Htxi1H-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Htxi1X-yEe6IE6AcCtnNjw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HtyJ4H-yEe6IE6AcCtnNjw" name="STATUS" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_HtyJ4X-yEe6IE6AcCtnNjw" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HtyJ4n-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HtyJ43-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HtyJ5H-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HtyJ5X-yEe6IE6AcCtnNjw" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Htyw8H-yEe6IE6AcCtnNjw" name="DATE_CREATION" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_Htyw8X-yEe6IE6AcCtnNjw" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Htyw8n-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HtzYAH-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HtzYAX-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HtzYAn-yEe6IE6AcCtnNjw" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Htz_EH-yEe6IE6AcCtnNjw" name="ID_FICHIER" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_Htz_EX-yEe6IE6AcCtnNjw" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Htz_En-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Htz_E3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Htz_FH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Htz_FX-yEe6IE6AcCtnNjw" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="__C8nEH-5Ee6IE6AcCtnNjw" name="SAS_EMAIL_PK">
        <node defType="com.stambia.rdbms.colref" id="__C8nEX-5Ee6IE6AcCtnNjw" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="__C8nEn-5Ee6IE6AcCtnNjw" ref="resource.md#_Htw7wH-yEe6IE6AcCtnNjw?fileId=_TkY50HozEe6i1bEIfNaCgQ$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.check" id="_NEAjAIq7Ee6UQ4O0GYlsJg" name="CTRL_EMAIL">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_NEAjAYq7Ee6UQ4O0GYlsJg" value="l'email doit etre valide"/>
        <attribute defType="com.stambia.rdbms.check.severity" id="_NEAjAoq7Ee6UQ4O0GYlsJg" value="200"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_NEAjA4q7Ee6UQ4O0GYlsJg" value="EMAIL NOT LIKE '%@%.%' "/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_NEAjBIq7Ee6UQ4O0GYlsJg" value="CTRL_EMAIL"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_NEAjBYq7Ee6UQ4O0GYlsJg" name="CTRL_FK_CLIENT">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_NEAjBoq7Ee6UQ4O0GYlsJg" value="le client doit exister"/>
        <attribute defType="com.stambia.rdbms.check.severity" id="_NEAjB4q7Ee6UQ4O0GYlsJg" value="200"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_NEAjCIq7Ee6UQ4O0GYlsJg" value="exists( select 1 from %x{md:objectPath($CSG1_ORA1.SAS_CLIENT, 'SAS_CLIENT')}x% b&#xD;&#xA;where CLE_CLIENT=b.CLE_CLIENT)"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_NEAjCYq7Ee6UQ4O0GYlsJg" value="CTRL_FK_CLIENT"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_NEAjCoq7Ee6UQ4O0GYlsJg" name="CTRL_STATUS">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_NEAjC4q7Ee6UQ4O0GYlsJg" value="le status email est obligatoire"/>
        <attribute defType="com.stambia.rdbms.check.severity" id="_NEBKEIq7Ee6UQ4O0GYlsJg" value="200"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_NEBKEYq7Ee6UQ4O0GYlsJg" value="STATUS is not null"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_NEBKEoq7Ee6UQ4O0GYlsJg" value="CTRL_STATUS"/>
      </node>
      <metaDataLink name="SAS" target="resource.md#_AHwtUH-qEe6IE6AcCtnNjw?fileId=_TkY50HozEe6i1bEIfNaCgQ$type=md$name=SAS?"/>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_HbPBUX-yEe6IE6AcCtnNjw" name="SAS_COMPTE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_HbPBUn-yEe6IE6AcCtnNjw" value="SAS_COMPTE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_HbPBU3-yEe6IE6AcCtnNjw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_HetMEH-yEe6IE6AcCtnNjw" name="TYPE_LIGNE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_HetMEX-yEe6IE6AcCtnNjw" value="TYPE_LIGNE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HetMEn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HetME3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HetMFH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HetMFX-yEe6IE6AcCtnNjw" value="3"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HeuaMH-yEe6IE6AcCtnNjw" name="ACTION" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_HeuaMX-yEe6IE6AcCtnNjw" value="ACTION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HeuaMn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HeuaM3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HeuaNH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HeuaNX-yEe6IE6AcCtnNjw" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HevBQH-yEe6IE6AcCtnNjw" name="CLE_COMPTE" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_HevBQX-yEe6IE6AcCtnNjw" value="CLE_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HevBQn-yEe6IE6AcCtnNjw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HevBQ3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HevBRH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HevBRX-yEe6IE6AcCtnNjw" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HevoUH-yEe6IE6AcCtnNjw" name="STATUS" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_HevoUX-yEe6IE6AcCtnNjw" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HevoUn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HevoU3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HevoVH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HevoVX-yEe6IE6AcCtnNjw" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HewPYH-yEe6IE6AcCtnNjw" name="TYPE" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_HewPYX-yEe6IE6AcCtnNjw" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HewPYn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HewPY3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HewPZH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HewPZX-yEe6IE6AcCtnNjw" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HexdgH-yEe6IE6AcCtnNjw" name="CABINET_RATTACHEMENT" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_HexdgX-yEe6IE6AcCtnNjw" value="CABINET_RATTACHEMENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Hexdgn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Hexdg3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HexdhH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HexdhX-yEe6IE6AcCtnNjw" value="9"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HeyEkH-yEe6IE6AcCtnNjw" name="DATE_CREATION" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_HeyEkX-yEe6IE6AcCtnNjw" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HeyEkn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HeyEk3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HeyElH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HeyElX-yEe6IE6AcCtnNjw" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HeyroH-yEe6IE6AcCtnNjw" name="ID_FICHIER" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_HeyroX-yEe6IE6AcCtnNjw" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Heyron-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Heyro3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HeyrpH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HeyrpX-yEe6IE6AcCtnNjw" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_-utccH-5Ee6IE6AcCtnNjw" name="SAS_COMPTE_PK">
        <node defType="com.stambia.rdbms.colref" id="_-utccX-5Ee6IE6AcCtnNjw" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_-utccn-5Ee6IE6AcCtnNjw" ref="resource.md#_HevBQH-yEe6IE6AcCtnNjw?fileId=_TkY50HozEe6i1bEIfNaCgQ$type=md$name=CLE_COMPTE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.check" id="_E8wIAIq7Ee6UQ4O0GYlsJg" name="CTRL_CABINET_RATTACHEMENT">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_E8wIAYq7Ee6UQ4O0GYlsJg" value="le cabinet de rattachement doit exister"/>
        <attribute defType="com.stambia.rdbms.check.severity" id="_E8wIAoq7Ee6UQ4O0GYlsJg" value="200"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_E8wIA4q7Ee6UQ4O0GYlsJg" value="exists( select 1 from %x{md:objectPath($CSG1_ORA1.TRANSCO, 'TRANSCO')}x% b&#xD;&#xA;where CABINET_RATTACHEMENT=b.CABINET_RATTACHEMENT)"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_E8wIBIq7Ee6UQ4O0GYlsJg" value="CTRL_CABINET_RATTACHEMENT"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_E8wIBYq7Ee6UQ4O0GYlsJg" name="CTRL_STATUS">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_E8wIBoq7Ee6UQ4O0GYlsJg" value="le status compte est obligatoire"/>
        <attribute defType="com.stambia.rdbms.check.severity" id="_E8wIB4q7Ee6UQ4O0GYlsJg" value="200"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_E8wICIq7Ee6UQ4O0GYlsJg" value="status is not null"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_E8wICYq7Ee6UQ4O0GYlsJg" value="CTRL_STATUS"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_E8wICoq7Ee6UQ4O0GYlsJg" name="CTRL_TYPE_CPT">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_E8wvEIq7Ee6UQ4O0GYlsJg" value="le type compte est obligatoire"/>
        <attribute defType="com.stambia.rdbms.check.severity" id="_E8wvEYq7Ee6UQ4O0GYlsJg" value="200"/>
        <attribute defType="com.stambia.rdbms.check.remarks" id="_E8wvEoq7Ee6UQ4O0GYlsJg" value="les null sont rejetés"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_E8wvE4q7Ee6UQ4O0GYlsJg" value="type is not null"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_E8wvFIq7Ee6UQ4O0GYlsJg" value="CTRL_TYPE_CPT"/>
      </node>
      <metaDataLink name="TRANSCO " target="resource.md#_JVVWQIUzEe6lN4vpMDZjAg?fileId=_TkY50HozEe6i1bEIfNaCgQ$type=md$name=TRANSCO%20?"/>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_HizB4X-yEe6IE6AcCtnNjw" name="SAS_ADRESSE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_HizB4n-yEe6IE6AcCtnNjw" value="SAS_ADRESSE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_HizB43-yEe6IE6AcCtnNjw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_Hma9oH-yEe6IE6AcCtnNjw" name="TYPE_LIGNE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_Hma9oX-yEe6IE6AcCtnNjw" value="TYPE_LIGNE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Hma9on-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Hma9o3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Hma9pH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Hma9pX-yEe6IE6AcCtnNjw" value="3"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HmbksH-yEe6IE6AcCtnNjw" name="ACTION" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_HmbksX-yEe6IE6AcCtnNjw" value="ACTION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HmcLwH-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HmcLwX-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HmcLwn-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HmcLw3-yEe6IE6AcCtnNjw" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HmcLxH-yEe6IE6AcCtnNjw" name="CLE_CLIENT" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_HmcLxX-yEe6IE6AcCtnNjw" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HmcLxn-yEe6IE6AcCtnNjw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HmcLx3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HmcLyH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HmcLyX-yEe6IE6AcCtnNjw" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Hmcy0H-yEe6IE6AcCtnNjw" name="STATUS" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_Hmcy0X-yEe6IE6AcCtnNjw" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Hmcy0n-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Hmcy03-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Hmcy1H-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Hmcy1X-yEe6IE6AcCtnNjw" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HmdZ4H-yEe6IE6AcCtnNjw" name="LIGNE_1" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_HmdZ4X-yEe6IE6AcCtnNjw" value="LIGNE_1"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HmdZ4n-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HmdZ43-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HmdZ5H-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HmdZ5X-yEe6IE6AcCtnNjw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HmeA8H-yEe6IE6AcCtnNjw" name="LIGNE_2" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_HmeA8X-yEe6IE6AcCtnNjw" value="LIGNE_2"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HmeA8n-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HmeA83-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HmeA9H-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HmeA9X-yEe6IE6AcCtnNjw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HmeA9n-yEe6IE6AcCtnNjw" name="LIGNE_3" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_HmeA93-yEe6IE6AcCtnNjw" value="LIGNE_3"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HmeA-H-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HmeA-X-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HmeA-n-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HmeA-3-yEe6IE6AcCtnNjw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HmeoAH-yEe6IE6AcCtnNjw" name="LIGNE_4" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_HmeoAX-yEe6IE6AcCtnNjw" value="LIGNE_4"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HmeoAn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HmeoA3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HmeoBH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HmeoBX-yEe6IE6AcCtnNjw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HmfPEH-yEe6IE6AcCtnNjw" name="LIGNE_5" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_HmfPEX-yEe6IE6AcCtnNjw" value="LIGNE_5"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HmfPEn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HmfPE3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HmfPFH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HmfPFX-yEe6IE6AcCtnNjw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Hmf2IH-yEe6IE6AcCtnNjw" name="VILLE" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_Hmf2IX-yEe6IE6AcCtnNjw" value="VILLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Hmf2In-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Hmf2I3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Hmf2JH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Hmf2JX-yEe6IE6AcCtnNjw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Hmf2Jn-yEe6IE6AcCtnNjw" name="CODE_POSTAL" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_Hmf2J3-yEe6IE6AcCtnNjw" value="CODE_POSTAL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Hmf2KH-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Hmf2KX-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Hmf2Kn-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Hmf2K3-yEe6IE6AcCtnNjw" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HmgdMH-yEe6IE6AcCtnNjw" name="PAYS" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_HmgdMX-yEe6IE6AcCtnNjw" value="PAYS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HmgdMn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HmgdM3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HmgdNH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HmgdNX-yEe6IE6AcCtnNjw" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HmgdNn-yEe6IE6AcCtnNjw" name="QUALITE" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_HmgdN3-yEe6IE6AcCtnNjw" value="QUALITE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HmgdOH-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HmgdOX-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HmgdOn-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HmgdO3-yEe6IE6AcCtnNjw" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HmhEQH-yEe6IE6AcCtnNjw" name="DATE_CREATION" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_HmhEQX-yEe6IE6AcCtnNjw" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HmhEQn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HmhEQ3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HmhERH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HmhERX-yEe6IE6AcCtnNjw" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HmhERn-yEe6IE6AcCtnNjw" name="ID_FICHIER" position="15">
        <attribute defType="com.stambia.rdbms.column.name" id="_HmhER3-yEe6IE6AcCtnNjw" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HmhESH-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HmhESX-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HmhESn-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HmhES3-yEe6IE6AcCtnNjw" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_-6M6wH-5Ee6IE6AcCtnNjw" name="SAS_ADRESSE_PK">
        <node defType="com.stambia.rdbms.colref" id="_-6M6wX-5Ee6IE6AcCtnNjw" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_-6M6wn-5Ee6IE6AcCtnNjw" ref="resource.md#_HmcLxH-yEe6IE6AcCtnNjw?fileId=_TkY50HozEe6i1bEIfNaCgQ$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.check" id="_5orywIq6Ee6UQ4O0GYlsJg" name="CTRL_STATUS">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_5orywYq6Ee6UQ4O0GYlsJg" value="le status de l'adresse est obligatoire"/>
        <attribute defType="com.stambia.rdbms.check.severity" id="_5orywoq6Ee6UQ4O0GYlsJg" value="200"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_5oryw4q6Ee6UQ4O0GYlsJg" value="STATUS is not null"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_5oryxIq6Ee6UQ4O0GYlsJg" value="CTRL_STATUS"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_HT2m8X-yEe6IE6AcCtnNjw" name="SAS_CLIENT">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_HT2m8n-yEe6IE6AcCtnNjw" value="SAS_CLIENT"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_HT2m83-yEe6IE6AcCtnNjw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_HXZDIH-yEe6IE6AcCtnNjw" name="TYPE_LIGNE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_HXZDIX-yEe6IE6AcCtnNjw" value="TYPE_LIGNE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HXZDIn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HXZDI3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HXZDJH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HXZDJX-yEe6IE6AcCtnNjw" value="3"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HXZDJn-yEe6IE6AcCtnNjw" name="ACTION" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_HXZDJ3-yEe6IE6AcCtnNjw" value="ACTION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HXZDKH-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HXZDKX-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HXZDKn-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HXZDK3-yEe6IE6AcCtnNjw" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HXZDLH-yEe6IE6AcCtnNjw" name="CLE_CLIENT" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_HXZDLX-yEe6IE6AcCtnNjw" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HXZDLn-yEe6IE6AcCtnNjw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HXZDL3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HXZDMH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HXZDMX-yEe6IE6AcCtnNjw" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HXZDMn-yEe6IE6AcCtnNjw" name="CLE_COMPTE" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_HXZDM3-yEe6IE6AcCtnNjw" value="CLE_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HXZDNH-yEe6IE6AcCtnNjw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HXZDNX-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HXZqMH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HXZqMX-yEe6IE6AcCtnNjw" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HXZqMn-yEe6IE6AcCtnNjw" name="STATUS" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_HXZqM3-yEe6IE6AcCtnNjw" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HXZqNH-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HXZqNX-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HXZqNn-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HXZqN3-yEe6IE6AcCtnNjw" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HXZqOH-yEe6IE6AcCtnNjw" name="TYPE" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_HXZqOX-yEe6IE6AcCtnNjw" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HXZqOn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HXZqO3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HXZqPH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HXZqPX-yEe6IE6AcCtnNjw" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HXZqPn-yEe6IE6AcCtnNjw" name="CIVILITE" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_HXZqP3-yEe6IE6AcCtnNjw" value="CIVILITE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HXZqQH-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HXZqQX-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HXZqQn-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HXZqQ3-yEe6IE6AcCtnNjw" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HXZqRH-yEe6IE6AcCtnNjw" name="PRENOM" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_HXZqRX-yEe6IE6AcCtnNjw" value="PRENOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HXZqRn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HXZqR3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HXZqSH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HXZqSX-yEe6IE6AcCtnNjw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HXaRQH-yEe6IE6AcCtnNjw" name="NOM" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_HXaRQX-yEe6IE6AcCtnNjw" value="NOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HXaRQn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HXaRQ3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HXaRRH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HXaRRX-yEe6IE6AcCtnNjw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HXaRRn-yEe6IE6AcCtnNjw" name="DATE_ANNIVERSAIRE" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_HXaRR3-yEe6IE6AcCtnNjw" value="DATE_ANNIVERSAIRE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HXaRSH-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HXaRSX-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HXaRSn-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HXaRS3-yEe6IE6AcCtnNjw" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HXaRTH-yEe6IE6AcCtnNjw" name="SEXE" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_HXaRTX-yEe6IE6AcCtnNjw" value="SEXE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HXaRTn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HXaRT3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HXaRUH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HXaRUX-yEe6IE6AcCtnNjw" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HXaRUn-yEe6IE6AcCtnNjw" name="MUTUELLE" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_HXaRU3-yEe6IE6AcCtnNjw" value="MUTUELLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HXaRVH-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HXaRVX-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HXaRVn-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HXaRV3-yEe6IE6AcCtnNjw" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HXaRWH-yEe6IE6AcCtnNjw" name="DATE_CREATION" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_HXaRWX-yEe6IE6AcCtnNjw" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HXaRWn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HXaRW3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HXaRXH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HXaRXX-yEe6IE6AcCtnNjw" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HXa4UH-yEe6IE6AcCtnNjw" name="ID_FICHIER" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_HXa4UX-yEe6IE6AcCtnNjw" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HXa4Un-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HXa4U3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HXa4VH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HXa4VX-yEe6IE6AcCtnNjw" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_-lvGoH-5Ee6IE6AcCtnNjw" name="SAS_CLIENT_PK">
        <node defType="com.stambia.rdbms.colref" id="_-lvGoX-5Ee6IE6AcCtnNjw" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_-lvGon-5Ee6IE6AcCtnNjw" ref="resource.md#_HXZDLH-yEe6IE6AcCtnNjw?fileId=_TkY50HozEe6i1bEIfNaCgQ$type=md$name=CLE_CLIENT?"/>
        </node>
        <node defType="com.stambia.rdbms.colref" id="_-lvGo3-5Ee6IE6AcCtnNjw" position="2">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_-lvGpH-5Ee6IE6AcCtnNjw" ref="resource.md#_HXZDMn-yEe6IE6AcCtnNjw?fileId=_TkY50HozEe6i1bEIfNaCgQ$type=md$name=CLE_COMPTE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.check" id="_-t7ORYq6Ee6UQ4O0GYlsJg" name="CTRL_FK_COMPTE">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_-t7ORoq6Ee6UQ4O0GYlsJg" value="le compte doit exister"/>
        <attribute defType="com.stambia.rdbms.check.severity" id="_-t7OR4q6Ee6UQ4O0GYlsJg" value="200"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_-t7OSIq6Ee6UQ4O0GYlsJg" value="exists( select 1 from %x{md:objectPath($CSG1_ORA1.SAS, 'SAS_COMPTE')}x% b&#xD;&#xA;where CLE_COMPTE=b.CLE_COMPTE)"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_-t7OSYq6Ee6UQ4O0GYlsJg" value="CTRL_FK_COMPTE"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_-t7OSoq6Ee6UQ4O0GYlsJg" name="CTRL_STATUS">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_-t7OS4q6Ee6UQ4O0GYlsJg" value="le status client est obligatoire"/>
        <attribute defType="com.stambia.rdbms.check.severity" id="_-t7OTIq6Ee6UQ4O0GYlsJg" value="200"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_-t7OTYq6Ee6UQ4O0GYlsJg" value="STATUS is not null"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_-t7OToq6Ee6UQ4O0GYlsJg" value="CTRL_STATUS"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_-t7OT4q6Ee6UQ4O0GYlsJg" name="CTRL_TYPE">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_-t7OUIq6Ee6UQ4O0GYlsJg" value="le type client est obligatoire"/>
        <attribute defType="com.stambia.rdbms.check.severity" id="_-t7OUYq6Ee6UQ4O0GYlsJg" value="200"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_-t7OUoq6Ee6UQ4O0GYlsJg" value="TYPE is not null"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_-t7OU4q6Ee6UQ4O0GYlsJg" value="CTRL_TYPE"/>
      </node>
      <metaDataLink name="SAS" target="resource.md#_AHwtUH-qEe6IE6AcCtnNjw?fileId=_TkY50HozEe6i1bEIfNaCgQ$type=md$name=SAS?"/>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_He_f8H-yEe6IE6AcCtnNjw" name="SAS_TELEPHONE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_HfAHAH-yEe6IE6AcCtnNjw" value="SAS_TELEPHONE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_HfAHAX-yEe6IE6AcCtnNjw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_Him0oH-yEe6IE6AcCtnNjw" name="TYPE_LIGNE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_Him0oX-yEe6IE6AcCtnNjw" value="TYPE_LIGNE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Him0on-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Him0o3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Him0pH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Him0pX-yEe6IE6AcCtnNjw" value="3"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HioCwH-yEe6IE6AcCtnNjw" name="ACTION" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_HioCwX-yEe6IE6AcCtnNjw" value="ACTION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HioCwn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HioCw3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HioCxH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HioCxX-yEe6IE6AcCtnNjw" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Hiop0H-yEe6IE6AcCtnNjw" name="CLE_CLIENT" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_Hiop0X-yEe6IE6AcCtnNjw" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Hiop0n-yEe6IE6AcCtnNjw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Hiop03-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Hiop1H-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Hiop1X-yEe6IE6AcCtnNjw" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HipQ4H-yEe6IE6AcCtnNjw" name="PHONE" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_HipQ4X-yEe6IE6AcCtnNjw" value="PHONE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HipQ4n-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HipQ43-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HipQ5H-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HipQ5X-yEe6IE6AcCtnNjw" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Hip38H-yEe6IE6AcCtnNjw" name="STATUS" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_Hip38X-yEe6IE6AcCtnNjw" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Hip38n-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Hip383-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Hip39H-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Hip39X-yEe6IE6AcCtnNjw" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HirGEH-yEe6IE6AcCtnNjw" name="FAVORI" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_HirGEX-yEe6IE6AcCtnNjw" value="FAVORI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HirGEn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HirGE3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HirGFH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HirGFX-yEe6IE6AcCtnNjw" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HirtIH-yEe6IE6AcCtnNjw" name="TYPE" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_HirtIX-yEe6IE6AcCtnNjw" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HirtIn-yEe6IE6AcCtnNjw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HirtI3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HirtJH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HirtJX-yEe6IE6AcCtnNjw" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HisUMH-yEe6IE6AcCtnNjw" name="DATE_CREATION" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_HisUMX-yEe6IE6AcCtnNjw" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HisUMn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HisUM3-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HisUNH-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HisUNX-yEe6IE6AcCtnNjw" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_His7QH-yEe6IE6AcCtnNjw" name="ID_FICHIER" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_His7QX-yEe6IE6AcCtnNjw" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_His7Qn-yEe6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HitiUH-yEe6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HitiUX-yEe6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HitiUn-yEe6IE6AcCtnNjw" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_-0SgAH-5Ee6IE6AcCtnNjw" name="SAS_TELEPHONE_PK">
        <node defType="com.stambia.rdbms.colref" id="_-0SgAX-5Ee6IE6AcCtnNjw" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_-0SgAn-5Ee6IE6AcCtnNjw" ref="resource.md#_Hiop0H-yEe6IE6AcCtnNjw?fileId=_TkY50HozEe6i1bEIfNaCgQ$type=md$name=CLE_CLIENT?"/>
        </node>
        <node defType="com.stambia.rdbms.colref" id="_-0SgA3-5Ee6IE6AcCtnNjw" position="2">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_-0SgBH-5Ee6IE6AcCtnNjw" ref="resource.md#_HirtIH-yEe6IE6AcCtnNjw?fileId=_TkY50HozEe6i1bEIfNaCgQ$type=md$name=TYPE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.check" id="_RHlGIIq7Ee6UQ4O0GYlsJg" name="CTRL_FAVORI">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_RHlGIYq7Ee6UQ4O0GYlsJg" value="le téléphone favori est obligatoire"/>
        <attribute defType="com.stambia.rdbms.check.severity" id="_RHlGIoq7Ee6UQ4O0GYlsJg" value="200"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_RHlGI4q7Ee6UQ4O0GYlsJg" value="FAVORI is not null"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_RHlGJIq7Ee6UQ4O0GYlsJg" value="CTRL_FAVORI"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_RHlGJYq7Ee6UQ4O0GYlsJg" name="CTRL_FK_CLIENT">
        <attribute defType="com.stambia.rdbms.check.sql" id="_RHlGJoq7Ee6UQ4O0GYlsJg" value="exists( select 1 from %x{md:objectPath($CSG1_ORA1.SAS_CLIENT, 'SAS_CLIENT')}x% b&#xD;&#xA;where CLE_CLIENT=b.CLE_CLIENT)"/>
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_RHlGJ4q7Ee6UQ4O0GYlsJg" value="le client doit exister"/>
        <attribute defType="com.stambia.rdbms.check.severity" id="_RHlGKIq7Ee6UQ4O0GYlsJg" value="200"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_RHlGKYq7Ee6UQ4O0GYlsJg" value="CTRL_FK_CLIENT"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_RHlGKoq7Ee6UQ4O0GYlsJg" name="CTRL_PHONE">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_RHlGK4q7Ee6UQ4O0GYlsJg" value="le numéro de téléphone est obligatoire"/>
        <attribute defType="com.stambia.rdbms.check.severity" id="_RHlGLIq7Ee6UQ4O0GYlsJg" value="200"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_RHlGLYq7Ee6UQ4O0GYlsJg" value="PHONE is not null"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_RHlGLoq7Ee6UQ4O0GYlsJg" value="CTRL_PHONE"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_RHlGL4q7Ee6UQ4O0GYlsJg" name="CTRL_STATUS">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_RHlGMIq7Ee6UQ4O0GYlsJg" value="le status téléphone est obligatoire"/>
        <attribute defType="com.stambia.rdbms.check.severity" id="_RHlGMYq7Ee6UQ4O0GYlsJg" value="200"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_RHlGMoq7Ee6UQ4O0GYlsJg" value="STATUS is not null "/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_RHlGM4q7Ee6UQ4O0GYlsJg" value="CTRL_STATUS"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_RHlGNIq7Ee6UQ4O0GYlsJg" name="CTRL_TYPE">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_RHltMIq7Ee6UQ4O0GYlsJg" value="le type téléphone est obligatoire"/>
        <attribute defType="com.stambia.rdbms.check.severity" id="_RHltMYq7Ee6UQ4O0GYlsJg" value="200"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_RHltMoq7Ee6UQ4O0GYlsJg" value="TYPE is not null"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_RHltM4q7Ee6UQ4O0GYlsJg" value="CTRL_TYPE"/>
      </node>
      <metaDataLink name="SAS" target="resource.md#_AHwtUH-qEe6IE6AcCtnNjw?fileId=_TkY50HozEe6i1bEIfNaCgQ$type=md$name=SAS?"/>
    </node>
  </node>
  <node defType="com.stambia.rdbms.schema" id="_-3pWAH-5Ee6IE6AcCtnNjw" name="ADM">
    <attribute defType="com.stambia.rdbms.schema.name" id="_FHKMQH-6Ee6IE6AcCtnNjw" value="CSG1_ORA1"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_Ayo_oIU3Ee6kybSjKPTayw" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_CzgEIIU3Ee6kybSjKPTayw" value="I_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_Dg-OIIU3Ee6kybSjKPTayw" value="R_[targetName]"/>
    <node defType="com.stambia.rdbms.datastore" id="_HVz1IX-6Ee6IE6AcCtnNjw" name="SOURCE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_HVz1In-6Ee6IE6AcCtnNjw" value="SOURCE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_HVz1I3-6Ee6IE6AcCtnNjw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_HZUcIH-6Ee6IE6AcCtnNjw" name="ID_FICHIER" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_HZUcIX-6Ee6IE6AcCtnNjw" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HZUcIn-6Ee6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_HZUcI3-6Ee6IE6AcCtnNjw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HZUcJH-6Ee6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HZUcJX-6Ee6IE6AcCtnNjw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HZUcJn-6Ee6IE6AcCtnNjw" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HZUcJ3-6Ee6IE6AcCtnNjw" name="LIBELLE_FICHIER" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_HZUcKH-6Ee6IE6AcCtnNjw" value="LIBELLE_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HZUcKX-6Ee6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HZUcKn-6Ee6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HZUcK3-6Ee6IE6AcCtnNjw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HZUcLH-6Ee6IE6AcCtnNjw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_HZVDMH-6Ee6IE6AcCtnNjw" name="DATE_CHARGEMENT_FICHIER" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_HZVDMX-6Ee6IE6AcCtnNjw" value="DATE_CHARGEMENT_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_HZVDMn-6Ee6IE6AcCtnNjw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_HZVDM3-6Ee6IE6AcCtnNjw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_HZVDNH-6Ee6IE6AcCtnNjw" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_HZVDNX-6Ee6IE6AcCtnNjw" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_v6-sfIq8Ee6UQ4O0GYlsJg" name="NB_LIGNES" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_v6-sfYq8Ee6UQ4O0GYlsJg" value="NB_LIGNES"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_v6-sfoq8Ee6UQ4O0GYlsJg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_v6-sf4q8Ee6UQ4O0GYlsJg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_v6-sgIq8Ee6UQ4O0GYlsJg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_v6-sgYq8Ee6UQ4O0GYlsJg" value="20"/>
      </node>
    </node>
  </node>
  <node defType="com.stambia.rdbms.schema" id="_JVVWQIUzEe6lN4vpMDZjAg" name="TRANSCO ">
    <attribute defType="com.stambia.rdbms.schema.name" id="_Q8jmUIUzEe6lN4vpMDZjAg" value="CSG1_ORA1"/>
    <attribute defType="com.stambia.rdbms.schema.dataStoreFilter" id="_Tf668IUzEe6lN4vpMDZjAg" value="TRANSCO%"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_BJR-AIU3Ee6kybSjKPTayw" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_CemLIIU3Ee6kybSjKPTayw" value="I_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_EiIJIIU3Ee6kybSjKPTayw" value="R_[targetName]"/>
    <node defType="com.stambia.rdbms.datastore" id="_XYqHEYUzEe6lN4vpMDZjAg" name="TRANSCO_SEXE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_XYqHEoUzEe6lN4vpMDZjAg" value="TRANSCO_SEXE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_XYqHE4UzEe6lN4vpMDZjAg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_Xb3zIIUzEe6lN4vpMDZjAg" name="SEXE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_Xb3zIYUzEe6lN4vpMDZjAg" value="SEXE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Xb3zIoUzEe6lN4vpMDZjAg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Xb3zI4UzEe6lN4vpMDZjAg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Xb3zJIUzEe6lN4vpMDZjAg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Xb3zJYUzEe6lN4vpMDZjAg" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Xb3zJoUzEe6lN4vpMDZjAg" name="LIIB_SEXE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_Xb3zJ4UzEe6lN4vpMDZjAg" value="LIIB_SEXE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Xb3zKIUzEe6lN4vpMDZjAg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Xb3zKYUzEe6lN4vpMDZjAg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Xb3zKoUzEe6lN4vpMDZjAg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Xb3zK4UzEe6lN4vpMDZjAg" value="255"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_Xb9SsYUzEe6lN4vpMDZjAg" name="TRANSCO_TYPE_CLIENT">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_Xb9SsoUzEe6lN4vpMDZjAg" value="TRANSCO_TYPE_CLIENT"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_Xb9Ss4UzEe6lN4vpMDZjAg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_XfUIsIUzEe6lN4vpMDZjAg" name="TYPE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_XfUIsYUzEe6lN4vpMDZjAg" value="TYPE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_XfUIsoUzEe6lN4vpMDZjAg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_XfUIs4UzEe6lN4vpMDZjAg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_XfUItIUzEe6lN4vpMDZjAg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_XfUItYUzEe6lN4vpMDZjAg" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_XfUvwIUzEe6lN4vpMDZjAg" name="LIB_TYPE_CLIENT" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_XfUvwYUzEe6lN4vpMDZjAg" value="LIB_TYPE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_XfUvwoUzEe6lN4vpMDZjAg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_XfUvw4UzEe6lN4vpMDZjAg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_XfUvxIUzEe6lN4vpMDZjAg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_XfUvxYUzEe6lN4vpMDZjAg" value="255"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_Xfd5sYUzEe6lN4vpMDZjAg" name="TRANSCO_CIVILITE_CLIENT">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_Xfd5soUzEe6lN4vpMDZjAg" value="TRANSCO_CIVILITE_CLIENT"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_Xfd5s4UzEe6lN4vpMDZjAg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_XjCLEIUzEe6lN4vpMDZjAg" name="CIVILITE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_XjCLEYUzEe6lN4vpMDZjAg" value="CIVILITE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_XjCLEoUzEe6lN4vpMDZjAg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_XjCLE4UzEe6lN4vpMDZjAg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_XjCLFIUzEe6lN4vpMDZjAg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_XjCLFYUzEe6lN4vpMDZjAg" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_XjDZMIUzEe6lN4vpMDZjAg" name="LIB_CIVILITE_CLIENT" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_XjDZMYUzEe6lN4vpMDZjAg" value="LIB_CIVILITE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_XjDZMoUzEe6lN4vpMDZjAg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_XjDZM4UzEe6lN4vpMDZjAg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_XjDZNIUzEe6lN4vpMDZjAg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_XjDZNYUzEe6lN4vpMDZjAg" value="255"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_XmiyEYUzEe6lN4vpMDZjAg" name="TRANSCO_COMTPE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_XmiyEoUzEe6lN4vpMDZjAg" value="TRANSCO_COMTPE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_XmiyE4UzEe6lN4vpMDZjAg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_Xp5oEIUzEe6lN4vpMDZjAg" name="TYPE_COMPTE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_Xp5oEYUzEe6lN4vpMDZjAg" value="TYPE_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Xp6PIIUzEe6lN4vpMDZjAg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Xp6PIYUzEe6lN4vpMDZjAg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Xp6PIoUzEe6lN4vpMDZjAg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Xp6PI4UzEe6lN4vpMDZjAg" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Xp62MIUzEe6lN4vpMDZjAg" name="LIB_TYPE_COMPTE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_Xp62MYUzEe6lN4vpMDZjAg" value="LIB_TYPE_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Xp62MoUzEe6lN4vpMDZjAg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Xp62M4UzEe6lN4vpMDZjAg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Xp62NIUzEe6lN4vpMDZjAg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Xp62NYUzEe6lN4vpMDZjAg" value="255"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_XjMjIYUzEe6lN4vpMDZjAg" name="TRANSCO_PAYS">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_XjMjIoUzEe6lN4vpMDZjAg" value="TRANSCO_PAYS"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_XjMjI4UzEe6lN4vpMDZjAg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_XmdSgIUzEe6lN4vpMDZjAg" name="PAYS_ADRESSE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_XmdSgYUzEe6lN4vpMDZjAg" value="PAYS_ADRESSE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_XmdSgoUzEe6lN4vpMDZjAg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_XmdSg4UzEe6lN4vpMDZjAg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_XmdShIUzEe6lN4vpMDZjAg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_XmdShYUzEe6lN4vpMDZjAg" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_XmdShoUzEe6lN4vpMDZjAg" name="LIB_PAYS" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_XmdSh4UzEe6lN4vpMDZjAg" value="LIB_PAYS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_XmdSiIUzEe6lN4vpMDZjAg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_XmdSiYUzEe6lN4vpMDZjAg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_XmdSioUzEe6lN4vpMDZjAg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_XmdSi4UzEe6lN4vpMDZjAg" value="255"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_XVal0IUzEe6lN4vpMDZjAg" name="TRANSCO_CABINET_RATTACHEMENT">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_XVal0YUzEe6lN4vpMDZjAg" value="TRANSCO_CABINET_RATTACHEMENT"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_XVal0oUzEe6lN4vpMDZjAg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_XYlOkIUzEe6lN4vpMDZjAg" name="CABINET_RATTACHEMENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_XYlOkYUzEe6lN4vpMDZjAg" value="CABINET_RATTACHEMENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_XYlOkoUzEe6lN4vpMDZjAg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_XYlOk4UzEe6lN4vpMDZjAg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_XYlOlIUzEe6lN4vpMDZjAg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_XYlOlYUzEe6lN4vpMDZjAg" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_XYlOloUzEe6lN4vpMDZjAg" name="LIB_CABINET" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_XYlOl4UzEe6lN4vpMDZjAg" value="LIB_CABINET"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_XYlOmIUzEe6lN4vpMDZjAg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_XYlOmYUzEe6lN4vpMDZjAg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_XYlOmoUzEe6lN4vpMDZjAg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_XYlOm4UzEe6lN4vpMDZjAg" value="255"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_bHJqcYq3Ee6iRfqSgb1Pvw" name="TRANSCO_TYPE_TEL">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_bHJqcoq3Ee6iRfqSgb1Pvw" value="TRANSCO_TYPE_TEL"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_bHJqc4q3Ee6iRfqSgb1Pvw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_bKggcIq3Ee6iRfqSgb1Pvw" name="TYPE_TEL" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_bKggcYq3Ee6iRfqSgb1Pvw" value="TYPE_TEL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bKggcoq3Ee6iRfqSgb1Pvw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bKggc4q3Ee6iRfqSgb1Pvw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bKggdIq3Ee6iRfqSgb1Pvw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bKggdYq3Ee6iRfqSgb1Pvw" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_bKhHgIq3Ee6iRfqSgb1Pvw" name="LIB_TEL" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_bKhHgYq3Ee6iRfqSgb1Pvw" value="LIB_TEL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_bKhHgoq3Ee6iRfqSgb1Pvw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_bKhHg4q3Ee6iRfqSgb1Pvw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_bKhHhIq3Ee6iRfqSgb1Pvw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_bKhHhYq3Ee6iRfqSgb1Pvw" value="255"/>
      </node>
    </node>
  </node>
  <node defType="com.stambia.rdbms.schema" id="_3lz64IqgEe6wS8JTT7vucg" name="CHECK">
    <attribute defType="com.stambia.rdbms.schema.name" id="_3lz64YqgEe6wS8JTT7vucg" value="CSG1_ORA1"/>
    <attribute defType="com.stambia.rdbms.schema.dataStoreFilter" id="_3lz64oqgEe6wS8JTT7vucg" value="%CHECK"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_3lz644qgEe6wS8JTT7vucg" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_3lz65IqgEe6wS8JTT7vucg" value="I_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_3lz65YqgEe6wS8JTT7vucg" value="R_[targetName]"/>
    <node defType="com.stambia.rdbms.datastore" id="_878SEYqgEe6wS8JTT7vucg" name="F_CLIENT_CHECK">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_878SEoqgEe6wS8JTT7vucg" value="F_CLIENT_CHECK"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_878SE4qgEe6wS8JTT7vucg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_9CrMMIqgEe6wS8JTT7vucg" name="FILE_NAME" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_9CrMMYqgEe6wS8JTT7vucg" value="FILE_NAME"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_9CrMMoqgEe6wS8JTT7vucg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_9CrMM4qgEe6wS8JTT7vucg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_9CrMNIqgEe6wS8JTT7vucg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_9CrMNYqgEe6wS8JTT7vucg" value="256"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_9CrMNoqgEe6wS8JTT7vucg" name="F1" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_9CrMN4qgEe6wS8JTT7vucg" value="F1"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_9CrMOIqgEe6wS8JTT7vucg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_9CrMOYqgEe6wS8JTT7vucg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_9CrMOoqgEe6wS8JTT7vucg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_9CrMO4qgEe6wS8JTT7vucg" value="256"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_9CrzQIqgEe6wS8JTT7vucg" name="F2" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_9CrzQYqgEe6wS8JTT7vucg" value="F2"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_9CrzQoqgEe6wS8JTT7vucg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_9CrzQ4qgEe6wS8JTT7vucg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_9CrzRIqgEe6wS8JTT7vucg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_9CrzRYqgEe6wS8JTT7vucg" value="256"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_9CrzRoqgEe6wS8JTT7vucg" name="F3" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_9CrzR4qgEe6wS8JTT7vucg" value="F3"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_9CrzSIqgEe6wS8JTT7vucg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_9CrzSYqgEe6wS8JTT7vucg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_9CrzSoqgEe6wS8JTT7vucg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_9CrzS4qgEe6wS8JTT7vucg" value="256"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_9CrzTIqgEe6wS8JTT7vucg" name="F4" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_9CrzTYqgEe6wS8JTT7vucg" value="F4"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_9CrzToqgEe6wS8JTT7vucg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_9CrzT4qgEe6wS8JTT7vucg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_9CrzUIqgEe6wS8JTT7vucg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_9CrzUYqgEe6wS8JTT7vucg" value="256"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_9CsaUIqgEe6wS8JTT7vucg" name="F5" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_9CsaUYqgEe6wS8JTT7vucg" value="F5"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_9CsaUoqgEe6wS8JTT7vucg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_9CsaU4qgEe6wS8JTT7vucg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_9CsaVIqgEe6wS8JTT7vucg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_9CsaVYqgEe6wS8JTT7vucg" value="256"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_9CsaVoqgEe6wS8JTT7vucg" name="F6" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_9CsaV4qgEe6wS8JTT7vucg" value="F6"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_9CsaWIqgEe6wS8JTT7vucg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_9CsaWYqgEe6wS8JTT7vucg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_9CsaWoqgEe6wS8JTT7vucg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_9CsaW4qgEe6wS8JTT7vucg" value="256"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_9CsaXIqgEe6wS8JTT7vucg" name="F7" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_9CsaXYqgEe6wS8JTT7vucg" value="F7"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_9CsaXoqgEe6wS8JTT7vucg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_9CsaX4qgEe6wS8JTT7vucg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_9CsaYIqgEe6wS8JTT7vucg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_9CsaYYqgEe6wS8JTT7vucg" value="256"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_9CtBYIqgEe6wS8JTT7vucg" name="F8" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_9CtBYYqgEe6wS8JTT7vucg" value="F8"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_9CtBYoqgEe6wS8JTT7vucg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_9CtBY4qgEe6wS8JTT7vucg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_9CtBZIqgEe6wS8JTT7vucg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_9CtBZYqgEe6wS8JTT7vucg" value="256"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_9CtBZoqgEe6wS8JTT7vucg" name="F9" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_9CtBZ4qgEe6wS8JTT7vucg" value="F9"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_9CtBaIqgEe6wS8JTT7vucg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_9CtBaYqgEe6wS8JTT7vucg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_9CtBaoqgEe6wS8JTT7vucg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_9CtBa4qgEe6wS8JTT7vucg" value="256"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_9CtBbIqgEe6wS8JTT7vucg" name="F10" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_9CtBbYqgEe6wS8JTT7vucg" value="F10"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_9CtBboqgEe6wS8JTT7vucg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_9CtBb4qgEe6wS8JTT7vucg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_9CtBcIqgEe6wS8JTT7vucg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_9CtBcYqgEe6wS8JTT7vucg" value="256"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_9CtBcoqgEe6wS8JTT7vucg" name="F11" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_9CtBc4qgEe6wS8JTT7vucg" value="F11"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_9CtBdIqgEe6wS8JTT7vucg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_9CtBdYqgEe6wS8JTT7vucg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_9CtBdoqgEe6wS8JTT7vucg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_9CtBd4qgEe6wS8JTT7vucg" value="256"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_9CtocIqgEe6wS8JTT7vucg" name="F12" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_9CtocYqgEe6wS8JTT7vucg" value="F12"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_9CtocoqgEe6wS8JTT7vucg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_9Ctoc4qgEe6wS8JTT7vucg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_9CtodIqgEe6wS8JTT7vucg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_9CtodYqgEe6wS8JTT7vucg" value="256"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_9CtodoqgEe6wS8JTT7vucg" name="F13" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_9Ctod4qgEe6wS8JTT7vucg" value="F13"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_9CtoeIqgEe6wS8JTT7vucg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_9CtoeYqgEe6wS8JTT7vucg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_9CtoeoqgEe6wS8JTT7vucg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_9Ctoe4qgEe6wS8JTT7vucg" value="256"/>
      </node>
    </node>
  </node>
</md:node>