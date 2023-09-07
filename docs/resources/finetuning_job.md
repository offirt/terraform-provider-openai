---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "openai_finetuning_job Resource - terraform-provider-openai"
subcategory: ""
description: |-
  Fine Tuning Job resource
---

# openai_finetuning_job (Resource)

Fine Tuning Job resource



<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `model` (String) Model Identifier
- `training_file` (String) Training File Identifier
- `validation_file` (String) Validation File Identifier
- `wait` (Boolean) Wait for Fine Tuning Job completion

### Read-Only

- `created_at` (Number) Created Time
- `fine_tuned_model` (String) Fine Tuned Model
- `finished_at` (Number) Finished Time
- `hyperparams` (Attributes) Hyperparams (see [below for nested schema](#nestedatt--hyperparams))
- `id` (String) Fine Tuning Job Identifier
- `object` (String) Object Type
- `organization_id` (String) Organization Id
- `result_files` (List of String) Result Files
- `status` (String) Status
- `suffix` (String) Suffix
- `trained_tokens` (Number) Trained Tokens

<a id="nestedatt--hyperparams"></a>
### Nested Schema for `hyperparams`

Read-Only:

- `n_epochs` (Number) N Epochs