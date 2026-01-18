EXAMPLE REQUEST

GET /api/v1/facilities?region=Gauteng&category=Health

EXAMPLE RESPONSE

{
  "status": "success",
  "data": [
    {
      "id": 101,
      "name": "Community Clinic A",
      "region": "Gauteng",
      "category": "Health",
      "services": ["HIV Testing", "Vaccinations"],
      "last_updated": "2025-08-01"
    }
  ]
}


