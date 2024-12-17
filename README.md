const { t, i18n } = useTranslation(); 

{getLocalizedContent(item.LanguageContent, "name")}

const getLocalizedContent = (languageContent, field) => {
    if (!languageContent) return "";
    return (
      languageContent[i18n.language]?.[field] ||
      languageContent.en?.[field] ||
      ""
    );
  };

http://192.168.100.209:5173//reset-password?token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY3NTM5MjdiMjdlNDViZjVkZGUxNzRlNiIsImlhdCI6MTczMzUzMzU1MCwiZXhwIjoxNzMzNTM3MTUwfQ.cOyX6Dpzt0IafZot4zwhzZvrh8wJC2uQ-HQhcZDvkqY
