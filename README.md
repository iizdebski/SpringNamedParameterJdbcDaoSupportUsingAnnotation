# SpringNamedParameterJdbcDaoSupportUsingAnnotation

Differs from previous version with

@Repository

public class EmployeeDAOImpl extends NamedParameterJdbcDaoSupport implements EmployeeDAO {

and 

@PostConstruct

public void init(){

setDataSource(dataSource);

}
