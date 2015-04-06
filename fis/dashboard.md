Dashboards 
===================================

# Building Multiple Dashboards for Vulnerability and Devices ( vul -> dev )
. globally matching for current/open vulnerabilities and open vulnerabilities by device. 
. 


# Evaluate the directory/controller/view layout
----------------------------------
- /dashboards 
----------------------------------
-   /vulnerability
-   /vulnerability/all
-   /vulnerability/search
-   /vulnerability/reports
-   /vulnerability/++ dashboard partial views
-   /vulnerability/++ grid view queries
----------------------------------
-   /device
-   /device/all (grid view)
-   /device/search
-   /device/reports
-   /device/++ dashboard partial views
-   /device/++ grid view queries
----------------------------------

#View Models 
---------------------------------
- GridViewModel
- GridItemViewModel
- GridPagingViewModel 

- VulnerabilityGridViewModel
- VulnerabilityGridItemViewModel

- DeviceGridViewModel 
- DeviceGridItemViewModel

- Dashboard


# Retrospective
- Add Title to Open Vulnerability Grid 
- Prepare to make Vulnerability Grid generic, and utilize the VulnerabilityGridViewModel : GridVieModel 
- VulnerabilityGridViewModel : List<VulnerabilityGridViewItem> 
- Include sorting, paging, and filtering generically within the GridViewModel ( for sub-types ) 
- Inlcude Sorting,Filtering, and Paging into a common helper for the Controllers, to enable passing queries to the Service. 
- The Service should support the concept of SFP (sorting,fitlering, paging)
- Consolidation of Dtos + Info + ViewModel structures. 
- Implement Unit Tests for the Dashboard indicator methods in the Repository and the service. 
- +++  


# Reusable Partial Vies by Dashboard Element Type 
-  

#  DataSet Types : 
   1. Header (tag) Aggregated
   2. Filter Query Set 
   3. All Dashboard elements will support drill in-s. 
   4. Build this in a generic way. We want to save time in this effort. 

# JavaScript Event Handler Groups 
- Drill in activator 
- Drill in refresh 

# Service and Repository 
- On click event handler for a drill in that allows us to properly. 
- This will cause an extension to the Vulnerability Grid
- We need to enable Sorting , Filtering, and querying. 
- This must maintain its self.

- 2D Datasets will indeed need to support the filtering. 
- Raphael.js clickable shapes with data atributes (? extend raphael to do this )
- 


# Services 
-  

# Repositories 
- 






# UX/UI 
# Link to the Reports and the Descriptions (Tom said he wanted this to be added, with JSON Objects) 
   - Atleast a stub of that into the sprint this week. 
   - 

<ul>
 <li>
 	<a href="#rdf/subject" class="rdf_subject">Subject</a>
	<a href="#rdf/predicate" class="rdf_predicte">Predicate</a>
	<a href="#rdf/object" class="rdf_object">Object</a>
 </li>
</ul>


