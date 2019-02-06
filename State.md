# Managing State

this.setState({
        houseValues: {
          ...this.state.groupValues, [event.target.id]: event.target.value, houseColor: '', houseSize: '', houseType: '',
         },
      });
