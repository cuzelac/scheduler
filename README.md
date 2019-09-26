## Notes

* CS paradigm is called ["Consraint Programming"](https://en.wikipedia.org/wiki/Constraint_programming)
    * the problem is called the [Nurse Scheduling Problem](https://en.wikipedia.org/wiki/Nurse_scheduling_problem)
    * there is an annual contest called [MiniZinc
      Challenge](https://www.minizinc.org/challenge.html) for Constraint
      Programming problems
    * MiniZinc is a modeling language for constraint solvers
        * article [Constraint Solving With
          MiniZinc](https://www.hillelwayne.com/post/minizinc/)
* OSS
    * [Z3](https://github.com/taw/z3)
        * Ruby
        * bindings for Z3, a C lib
        * gem install works
    * OptaPlanner
        * Java
        * Looks like it's the industry standard
        * [video on Nurse Scheduling Problem](https://www.youtube.com/watch?v=7nPagqJK3bs
        * [github](https://github.com/kiegroup/optaplanner)
    * [CSP::Solver](https://github.com/komputerwiz/csp-solver)
        * Ruby
        * only solves for hard constraints
        * last commit: July 2017
            * no relevant forks
        * [Discussion of NSP](https://github.com/komputerwiz/csp-solver/issues/2)
    * [Cbc](https://github.com/gverger/ruby-cbc)
        * Ruby
        * only solves for hard constraints
        * last commit: June 2018
            * no relevant forks
    * [Geocode/R](https://github.com/alau/gecoder)
        * Ruby bindings for Geocode
        * deprecated
    * [OR-Tools](https://developers.google.com/optimization/)
        * CP library
        * won most recent MiniZinc challenge in multiple categories
    * MiniZinc
        * language to describe constraint problems
        * [python tutorial](https://www.hillelwayne.com/post/minizinc/)

* https://softwareengineering.stackexchange.com/questions/236668/what-algorithm-should-i-use-to-create-an-automatic-staff-scheduling-feature
* https://www.project.net/introduction-algorithms-solving-schedule-related-problems
* https://webcache.googleusercontent.com/search?q=cache:Pc0_JEnAAbsJ:https://pdfs.semanticscholar.org/61b2/366af2d454f59cfe800531a61e9d32e81911.pdf+&cd=15&hl=en&ct=clnk&gl=us&client=firefox-b-1-d
