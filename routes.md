login: `${server}/auth/login`,
signup: `${server}/auth/signup`,

uploadResume: `${server}/upload/resume`,
uploadProfileImage: `${server}/upload/profile`,

jobs: `${server}/api/jobs`,
post `${server}/api/jobs` #add new job
get `${server}/api/jobs` # to get all the jobs [for recruiter personal and for everyone]
get `${server}/api/jobs/:id` # to get info about a particular job
put `${server}/api/jobs/:id` # to update info of a particular job
delete `${server}/api/jobs/:id` # to delete a job

get `${server}/api/user` # get user's personal details
get `${server}/api/user/:id` // get user details from id
put `${server}/api/user` // update user details

post `${server}/api/jobs/:id/applications` # apply for a job [todo: test: done]
get `${server}/api/jobs/:id/applications` # recruiter gets applications for a particular job [todo: test: done]
get `${server}/api/applications` # recruiter/applicant gets all his applications
put `${server}/api/applications/:id` # update status of application: [Applicant: Can cancel, Recruiter: Can do everything] [todo: test: done]
get `${server}/api/applicants` # get a list of final applicants for current job : recruiter and get a list of final applicants for all his jobs : recruiter
