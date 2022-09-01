# get-to-know-total-number-of-members-for-each-category

SELECT count(*),list_professions.name FROM `users_data`, list_professions WHERE list_professions.profession_id = users_data.profession_id GROUP BY list_professions.name
