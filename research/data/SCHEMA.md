# Fields

`id` stable identifier; `title` listed/normalized activity; `operator` tour business; `region` one of Chania/Rethymno/Heraklion/Lasithi; `place` public locality; `category`, `terrain`; `price_eur` numeric published entry or null; `price_basis` unit and VAT condition; `price_status` published/unverified; `duration`; `season`; `summer_relevant`; `setup_complexity` low/medium/high; `starting_fit` subjective business inspiration, adjustable in interface; `description`; `source_url` public operator page; `photo_url` original externally linked image when identified; `photo_credit`, `photo_source_url`; `location_precision` area/village/region (not private property); `source_type` operator/agency; `checked_at` YYYY-MM-DD; `status`, `notes`, `tags` placeholders. 

Import JSON format: `{ "schema":"crete-experience-db/v1", "last_researched":"YYYY-MM-DD", "records":[...fields above...] }` or an array of full records. The browser merges using `id` or matching title+URL. Keep stable IDs.
