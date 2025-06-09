# webui-1727

This bundle includes a custom version of the advanced_document_content page provider that has aggregates for dc:nature, dc:coverage and dc:subjects, and a custom version of nuxeo-workspace-view-layout.html
 that has added nuxeo-data-table-column objects for these three aggregates

Directions
 * install Nuxeo with 'nuxeo-csv'
 * build this (mvn install) and place webui-1727-2023.31.16.jar in nxserver/bundles
 * create a workspace and import data.csv
 * observe data table columns with aggregation data
