# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.005 ops/ms
# Warmup Iteration   2: 5.501 ops/ms
# Warmup Iteration   3: 8.867 ops/ms
Iteration   1: 9.490 ops/ms
Iteration   2: 9.673 ops/ms
Iteration   3: 9.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.533 ±(99.9%) 2.257 ops/ms [Average]
  (min, avg, max) = (9.437, 9.533, 9.673), stdev = 0.124
  CI (99.9%): [7.276, 11.790] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.123 ops/ms
# Warmup Iteration   2: 8.868 ops/ms
# Warmup Iteration   3: 9.712 ops/ms
Iteration   1: 9.961 ops/ms
Iteration   2: 9.692 ops/ms
Iteration   3: 9.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.808 ±(99.9%) 2.526 ops/ms [Average]
  (min, avg, max) = (9.692, 9.808, 9.961), stdev = 0.138
  CI (99.9%): [7.283, 12.334] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.871 ops/ms
# Warmup Iteration   2: 8.059 ops/ms
# Warmup Iteration   3: 9.261 ops/ms
Iteration   1: 9.463 ops/ms
Iteration   2: 9.349 ops/ms
Iteration   3: 9.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.438 ±(99.9%) 1.443 ops/ms [Average]
  (min, avg, max) = (9.349, 9.438, 9.502), stdev = 0.079
  CI (99.9%): [7.994, 10.881] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.706 ops/ms
# Warmup Iteration   2: 6.836 ops/ms
# Warmup Iteration   3: 7.825 ops/ms
Iteration   1: 7.733 ops/ms
Iteration   2: 7.906 ops/ms
Iteration   3: 8.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.922 ±(99.9%) 3.594 ops/ms [Average]
  (min, avg, max) = (7.733, 7.922, 8.126), stdev = 0.197
  CI (99.9%): [4.328, 11.516] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.282 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.445 ±(99.9%) 0.006 ms/op
Iteration   1: 3.423 ±(99.9%) 0.006 ms/op
Iteration   2: 3.509 ±(99.9%) 0.003 ms/op
Iteration   3: 3.352 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.428 ±(99.9%) 1.435 ms/op [Average]
  (min, avg, max) = (3.352, 3.428, 3.509), stdev = 0.079
  CI (99.9%): [1.993, 4.863] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 10.173 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.009 ms/op
Iteration   1: 3.462 ±(99.9%) 0.002 ms/op
Iteration   2: 3.285 ±(99.9%) 0.007 ms/op
Iteration   3: 3.248 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.331 ±(99.9%) 2.091 ms/op [Average]
  (min, avg, max) = (3.248, 3.331, 3.462), stdev = 0.115
  CI (99.9%): [1.240, 5.423] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.620 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.572 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.008 ms/op
Iteration   1: 3.411 ±(99.9%) 0.006 ms/op
Iteration   2: 3.329 ±(99.9%) 0.011 ms/op
Iteration   3: 3.397 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.379 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (3.329, 3.379, 3.411), stdev = 0.044
  CI (99.9%): [2.572, 4.186] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.606 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.383 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.012 ms/op
Iteration   1: 4.026 ±(99.9%) 0.014 ms/op
Iteration   2: 3.909 ±(99.9%) 0.014 ms/op
Iteration   3: 3.916 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.951 ±(99.9%) 1.193 ms/op [Average]
  (min, avg, max) = (3.909, 3.951, 4.026), stdev = 0.065
  CI (99.9%): [2.758, 5.143] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.353 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.907 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.012 ms/op
Iteration   1: 3.442 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  21.925 ms/op
                 createUser·p0.9999: 25.625 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   2: 3.533 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  22.249 ms/op
                 createUser·p0.9999: 27.294 ms/op
                 createUser·p1.00:   27.492 ms/op

Iteration   3: 3.543 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  19.095 ms/op
                 createUser·p0.9999: 25.427 ms/op
                 createUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273608
  mean =      3.505 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8135 
    [ 2.500,  5.000) = 259870 
    [ 5.000,  7.500) = 4704 
    [ 7.500, 10.000) = 411 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 107 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     20.231 ms/op
     p(99.9900) =     26.584 ms/op
     p(99.9990) =     27.411 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.828 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.717 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.294 ±(99.9%) 0.008 ms/op
Iteration   1: 3.375 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.442 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  8.929 ms/op
                 existUser·p0.9999: 20.693 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   2: 3.373 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   6.463 ms/op
                 existUser·p0.999:  19.896 ms/op
                 existUser·p0.9999: 22.660 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   3: 3.198 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.221 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  15.173 ms/op
                 existUser·p0.9999: 29.557 ms/op
                 existUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289598
  mean =      3.313 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3502 
    [ 2.500,  5.000) = 280594 
    [ 5.000,  7.500) = 4541 
    [ 7.500, 10.000) = 546 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     13.061 ms/op
     p(99.9900) =     28.378 ms/op
     p(99.9990) =     30.835 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.221 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.451 ±(99.9%) 0.010 ms/op
Iteration   1: 3.337 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.469 ms/op
                 getUser·p0.999:  20.010 ms/op
                 getUser·p0.9999: 27.440 ms/op
                 getUser·p1.00:   28.082 ms/op

Iteration   2: 3.348 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.456 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  22.466 ms/op
                 getUser·p0.9999: 26.277 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   3: 3.382 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.780 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   4.092 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  8.672 ms/op
                 getUser·p0.9999: 24.790 ms/op
                 getUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 285940
  mean =      3.356 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10670 
    [ 2.500,  5.000) = 269907 
    [ 5.000,  7.500) = 4584 
    [ 7.500, 10.000) = 427 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 137 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     10.617 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     27.792 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.852 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.463 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.175 ±(99.9%) 0.012 ms/op
Iteration   1: 4.059 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  20.578 ms/op
                 listUser·p0.9999: 38.215 ms/op
                 listUser·p1.00:   40.042 ms/op

Iteration   2: 4.020 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  15.475 ms/op
                 listUser·p0.9999: 18.814 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   3: 3.875 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.429 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  13.566 ms/op
                 listUser·p0.9999: 15.917 ms/op
                 listUser·p1.00:   16.335 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240739
  mean =      3.983 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 232465 
    [ 5.000, 10.000) = 7505 
    [10.000, 15.000) = 498 
    [15.000, 20.000) = 168 
    [20.000, 25.000) = 71 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     15.615 ms/op
     p(99.9900) =     35.783 ms/op
     p(99.9990) =     39.171 ms/op
     p(99.9999) =     40.042 ms/op
    p(100.0000) =     40.042 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.533 ± 2.257  ops/ms
ClientPb.existUser                       thrpt       3   9.808 ± 2.526  ops/ms
ClientPb.getUser                         thrpt       3   9.438 ± 1.443  ops/ms
ClientPb.listUser                        thrpt       3   7.922 ± 3.594  ops/ms
ClientPb.createUser                       avgt       3   3.428 ± 1.435   ms/op
ClientPb.existUser                        avgt       3   3.331 ± 2.091   ms/op
ClientPb.getUser                          avgt       3   3.379 ± 0.807   ms/op
ClientPb.listUser                         avgt       3   3.951 ± 1.193   ms/op
ClientPb.createUser                     sample  273608   3.505 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.139           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.137           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.759           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.231           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.584           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.492           ms/op
ClientPb.existUser                      sample  289598   3.313 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.075           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.977           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.693           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.061           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.378           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.080           ms/op
ClientPb.getUser                        sample  285940   3.356 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.118           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.562           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.617           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.345           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.082           ms/op
ClientPb.listUser                       sample  240739   3.983 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.556           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.365           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.615           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.783           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.042           ms/op
