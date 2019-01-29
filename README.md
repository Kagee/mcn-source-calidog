Source: Access to the BigQuery dataset mentioned in https://medium.com/cali-dog-security/retrieving-storing-and-querying-250m-certificates-like-a-boss-31b1ce2dfcf8

BigQuery: SELECT all_dns_names FROM [ctl-lists:ctl_data.cert_data] WHERE REGEXP_MATCH( all_dns_names,r'\.no( |$)')

Credit: The result contains data from Cali Dog Security's work on certificate transparency logs.
