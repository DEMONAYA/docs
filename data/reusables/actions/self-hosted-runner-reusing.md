Alternatively, if you don't have access to the repository{% ifversion fpt %} or organization{% elsif ghes or ghec or ghae %}, organization, or enterprise{% endif %} on {% data variables.product.product_name %} to remove a runner, but you would like to re-use the runner machine, then you can delete the `.runner` file inside the self-hosted runner application directory. This allows the runner to be registered without having to re-download the self-hosted runner application.