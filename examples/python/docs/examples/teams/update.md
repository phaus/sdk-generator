from appwrite.client import Client
from appwrite.services.teams import Teams

client = Client()

(client
  .set_project('')
)

teams = Teams(client)

result = teams.update('[TEAM_ID]', '[NAME]')