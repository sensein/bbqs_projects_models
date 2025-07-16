```mermaid
erDiagram
Project {
    string award_id  
    stringList principle_investigators  
    stringList investigators  
    stringList presentations  
    string abstract  
    string website  
    string NIH_report  
    string study_human  
    string study_species  
    stringList use_sensors  
    string use_approaches  
    stringList produce_data_modality  
    stringList produce_data_type  
    stringList develope_hardware_type  
    stringList develope_software_type  
    stringList use_analysis_method  
    stringList use_analysis_types  
}
Collaborator {
    string name  
    string email  
    string organization  
    string ORCID_id  
}
Team {

}
Species {
    string id  
    string name  
    string full_name  
}
Abstract {
    string id  
    string contents  
    string keywords  
}



```

