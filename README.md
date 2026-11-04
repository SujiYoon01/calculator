    else if (EXCLUDE_DEPTS.includes((p.dept || '').replace(/\s+/g, ''))) reason = '제외 부서(' + p.dept + ')';
