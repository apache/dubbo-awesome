# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.734 ops/ms
# Warmup Iteration   2: 3.290 ops/ms
# Warmup Iteration   3: 7.162 ops/ms
Iteration   1: 7.408 ops/ms
Iteration   2: 7.908 ops/ms
Iteration   3: 7.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.722 ±(99.9%) 4.996 ops/ms [Average]
  (min, avg, max) = (7.408, 7.722, 7.908), stdev = 0.274
  CI (99.9%): [2.727, 12.718] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.200 ops/ms
# Warmup Iteration   2: 6.376 ops/ms
# Warmup Iteration   3: 8.018 ops/ms
Iteration   1: 7.792 ops/ms
Iteration   2: 8.162 ops/ms
Iteration   3: 8.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.009 ±(99.9%) 3.524 ops/ms [Average]
  (min, avg, max) = (7.792, 8.009, 8.162), stdev = 0.193
  CI (99.9%): [4.485, 11.533] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.038 ops/ms
# Warmup Iteration   2: 6.136 ops/ms
# Warmup Iteration   3: 7.587 ops/ms
Iteration   1: 7.589 ops/ms
Iteration   2: 7.724 ops/ms
Iteration   3: 7.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.675 ±(99.9%) 1.363 ops/ms [Average]
  (min, avg, max) = (7.589, 7.675, 7.724), stdev = 0.075
  CI (99.9%): [6.312, 9.038] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.204 ops/ms
# Warmup Iteration   2: 5.029 ops/ms
# Warmup Iteration   3: 6.415 ops/ms
Iteration   1: 6.568 ops/ms
Iteration   2: 6.746 ops/ms
Iteration   3: 6.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.640 ±(99.9%) 1.707 ops/ms [Average]
  (min, avg, max) = (6.568, 6.640, 6.746), stdev = 0.094
  CI (99.9%): [4.933, 8.348] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 14.035 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.539 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.466 ±(99.9%) 0.004 ms/op
Iteration   1: 4.281 ±(99.9%) 0.004 ms/op
Iteration   2: 4.187 ±(99.9%) 0.006 ms/op
Iteration   3: 4.099 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.189 ±(99.9%) 1.656 ms/op [Average]
  (min, avg, max) = (4.099, 4.189, 4.281), stdev = 0.091
  CI (99.9%): [2.532, 5.845] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 13.921 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.610 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.052 ±(99.9%) 0.004 ms/op
Iteration   1: 3.938 ±(99.9%) 0.005 ms/op
Iteration   2: 3.971 ±(99.9%) 0.004 ms/op
Iteration   3: 3.966 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.958 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (3.938, 3.958, 3.971), stdev = 0.018
  CI (99.9%): [3.632, 4.285] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 13.485 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.095 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.156 ±(99.9%) 0.005 ms/op
Iteration   1: 4.048 ±(99.9%) 0.004 ms/op
Iteration   2: 4.164 ±(99.9%) 0.005 ms/op
Iteration   3: 4.065 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.092 ±(99.9%) 1.143 ms/op [Average]
  (min, avg, max) = (4.048, 4.092, 4.164), stdev = 0.063
  CI (99.9%): [2.950, 5.235] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 16.246 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.557 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.898 ±(99.9%) 0.006 ms/op
Iteration   1: 4.911 ±(99.9%) 0.007 ms/op
Iteration   2: 4.890 ±(99.9%) 0.008 ms/op
Iteration   3: 4.852 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.884 ±(99.9%) 0.544 ms/op [Average]
  (min, avg, max) = (4.852, 4.884, 4.911), stdev = 0.030
  CI (99.9%): [4.340, 5.428] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 12.111 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 5.248 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.409 ±(99.9%) 0.018 ms/op
Iteration   1: 4.173 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.690 ms/op
                 createUser·p0.50:   3.961 ms/op
                 createUser·p0.90:   4.923 ms/op
                 createUser·p0.95:   5.636 ms/op
                 createUser·p0.99:   7.832 ms/op
                 createUser·p0.999:  25.254 ms/op
                 createUser·p0.9999: 29.393 ms/op
                 createUser·p1.00:   30.015 ms/op

Iteration   2: 4.048 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.722 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   7.438 ms/op
                 createUser·p0.999:  28.509 ms/op
                 createUser·p0.9999: 30.609 ms/op
                 createUser·p1.00:   31.949 ms/op

Iteration   3: 4.071 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.677 ms/op
                 createUser·p0.50:   3.908 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   7.740 ms/op
                 createUser·p0.999:  16.341 ms/op
                 createUser·p0.9999: 35.324 ms/op
                 createUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234149
  mean =      4.096 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 486 
    [ 2.500,  5.000) = 217593 
    [ 5.000,  7.500) = 13436 
    [ 7.500, 10.000) = 1879 
    [10.000, 12.500) = 367 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 102 
    [30.000, 32.500) = 56 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.677 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     25.539 ms/op
     p(99.9900) =     34.537 ms/op
     p(99.9990) =     35.826 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 13.294 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 5.193 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.015 ms/op
Iteration   1: 3.915 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.923 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.889 ms/op
                 existUser·p0.99:   8.159 ms/op
                 existUser·p0.999:  11.736 ms/op
                 existUser·p0.9999: 28.170 ms/op
                 existUser·p1.00:   28.541 ms/op

Iteration   2: 4.010 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.487 ms/op
                 existUser·p0.50:   3.838 ms/op
                 existUser·p0.90:   4.571 ms/op
                 existUser·p0.95:   4.973 ms/op
                 existUser·p0.99:   7.315 ms/op
                 existUser·p0.999:  20.153 ms/op
                 existUser·p0.9999: 30.704 ms/op
                 existUser·p1.00:   31.425 ms/op

Iteration   3: 4.009 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.653 ms/op
                 existUser·p0.50:   3.912 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   4.964 ms/op
                 existUser·p0.99:   7.455 ms/op
                 existUser·p0.999:  13.189 ms/op
                 existUser·p0.9999: 33.194 ms/op
                 existUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241473
  mean =      3.978 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 246 
    [ 2.500,  5.000) = 229763 
    [ 5.000,  7.500) = 8820 
    [ 7.500, 10.000) = 1992 
    [10.000, 12.500) = 344 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 67 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.487 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      7.752 ms/op
     p(99.9000) =     14.854 ms/op
     p(99.9900) =     32.528 ms/op
     p(99.9990) =     33.866 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 11.663 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 5.257 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.470 ±(99.9%) 0.019 ms/op
Iteration   1: 4.122 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.743 ms/op
                 getUser·p0.50:   3.912 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.669 ms/op
                 getUser·p0.99:   8.585 ms/op
                 getUser·p0.999:  21.692 ms/op
                 getUser·p0.9999: 30.588 ms/op
                 getUser·p1.00:   31.162 ms/op

Iteration   2: 4.189 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   4.026 ms/op
                 getUser·p0.90:   4.727 ms/op
                 getUser·p0.95:   5.202 ms/op
                 getUser·p0.99:   8.749 ms/op
                 getUser·p0.999:  14.279 ms/op
                 getUser·p0.9999: 31.395 ms/op
                 getUser·p1.00:   33.686 ms/op

Iteration   3: 3.995 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.513 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  32.765 ms/op
                 getUser·p0.9999: 35.127 ms/op
                 getUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233998
  mean =      4.100 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 220710 
    [ 5.000,  7.500) = 9868 
    [ 7.500, 10.000) = 2480 
    [10.000, 12.500) = 366 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 78 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      8.258 ms/op
     p(99.9000) =     21.692 ms/op
     p(99.9900) =     34.708 ms/op
     p(99.9990) =     35.324 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.492 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 5.977 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.088 ±(99.9%) 0.018 ms/op
Iteration   1: 4.950 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.966 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  28.606 ms/op
                 listUser·p0.9999: 30.951 ms/op
                 listUser·p1.00:   31.916 ms/op

Iteration   2: 4.868 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.544 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   6.627 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  21.045 ms/op
                 listUser·p0.9999: 25.854 ms/op
                 listUser·p1.00:   26.935 ms/op

Iteration   3: 4.883 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.601 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  17.807 ms/op
                 listUser·p0.9999: 20.200 ms/op
                 listUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 195783
  mean =      4.900 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 142305 
    [ 5.000,  7.500) = 47685 
    [ 7.500, 10.000) = 4536 
    [10.000, 12.500) = 641 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.544 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      5.489 ms/op
     p(95.0000) =      6.095 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     21.033 ms/op
     p(99.9900) =     29.931 ms/op
     p(99.9990) =     31.571 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.722 ± 4.996  ops/ms
ClientPb.existUser                       thrpt       3   8.009 ± 3.524  ops/ms
ClientPb.getUser                         thrpt       3   7.675 ± 1.363  ops/ms
ClientPb.listUser                        thrpt       3   6.640 ± 1.707  ops/ms
ClientPb.createUser                       avgt       3   4.189 ± 1.656   ms/op
ClientPb.existUser                        avgt       3   3.958 ± 0.327   ms/op
ClientPb.getUser                          avgt       3   4.092 ± 1.143   ms/op
ClientPb.listUser                         avgt       3   4.884 ± 0.544   ms/op
ClientPb.createUser                     sample  234149   4.096 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.677           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.760           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.259           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.709           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.539           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.537           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.045           ms/op
ClientPb.existUser                      sample  241473   3.978 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.487           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.489           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.956           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.752           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.854           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.528           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.079           ms/op
ClientPb.getUser                        sample  233998   4.100 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.339           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.112           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.258           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.692           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.708           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.586           ms/op
ClientPb.listUser                       sample  195783   4.900 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.544           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.095           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.044           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.033           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.931           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.916           ms/op
