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
# Warmup Iteration   1: 1.047 ops/ms
# Warmup Iteration   2: 2.224 ops/ms
# Warmup Iteration   3: 4.972 ops/ms
Iteration   1: 5.339 ops/ms
Iteration   2: 5.636 ops/ms
Iteration   3: 5.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.552 ±(99.9%) 3.403 ops/ms [Average]
  (min, avg, max) = (5.339, 5.552, 5.682), stdev = 0.187
  CI (99.9%): [2.149, 8.956] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.623 ops/ms
# Warmup Iteration   2: 5.085 ops/ms
# Warmup Iteration   3: 5.838 ops/ms
Iteration   1: 6.068 ops/ms
Iteration   2: 6.132 ops/ms
Iteration   3: 6.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.125 ±(99.9%) 0.979 ops/ms [Average]
  (min, avg, max) = (6.068, 6.125, 6.175), stdev = 0.054
  CI (99.9%): [5.146, 7.104] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.525 ops/ms
# Warmup Iteration   2: 4.607 ops/ms
# Warmup Iteration   3: 5.636 ops/ms
Iteration   1: 5.762 ops/ms
Iteration   2: 5.719 ops/ms
Iteration   3: 5.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.746 ±(99.9%) 0.438 ops/ms [Average]
  (min, avg, max) = (5.719, 5.746, 5.762), stdev = 0.024
  CI (99.9%): [5.309, 6.184] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.550 ops/ms
# Warmup Iteration   2: 4.111 ops/ms
# Warmup Iteration   3: 4.919 ops/ms
Iteration   1: 4.765 ops/ms
Iteration   2: 4.820 ops/ms
Iteration   3: 4.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.850 ±(99.9%) 1.893 ops/ms [Average]
  (min, avg, max) = (4.765, 4.850, 4.966), stdev = 0.104
  CI (99.9%): [2.957, 6.743] (assumes normal distribution)


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
# Warmup Iteration   1: 18.954 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 6.476 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.950 ±(99.9%) 0.005 ms/op
Iteration   1: 5.488 ±(99.9%) 0.007 ms/op
Iteration   2: 5.535 ±(99.9%) 0.010 ms/op
Iteration   3: 5.445 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.489 ±(99.9%) 0.814 ms/op [Average]
  (min, avg, max) = (5.445, 5.489, 5.535), stdev = 0.045
  CI (99.9%): [4.675, 6.303] (assumes normal distribution)


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
# Warmup Iteration   1: 19.435 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 6.432 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.751 ±(99.9%) 0.006 ms/op
Iteration   1: 5.382 ±(99.9%) 0.014 ms/op
Iteration   2: 5.227 ±(99.9%) 0.011 ms/op
Iteration   3: 5.421 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.343 ±(99.9%) 1.872 ms/op [Average]
  (min, avg, max) = (5.227, 5.343, 5.421), stdev = 0.103
  CI (99.9%): [3.471, 7.215] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.653 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 6.474 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.687 ±(99.9%) 0.012 ms/op
Iteration   1: 5.775 ±(99.9%) 0.005 ms/op
Iteration   2: 5.845 ±(99.9%) 0.011 ms/op
Iteration   3: 5.786 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.802 ±(99.9%) 0.684 ms/op [Average]
  (min, avg, max) = (5.775, 5.802, 5.845), stdev = 0.037
  CI (99.9%): [5.118, 6.486] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 19.650 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 8.008 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.918 ±(99.9%) 0.008 ms/op
Iteration   1: 6.619 ±(99.9%) 0.010 ms/op
Iteration   2: 6.565 ±(99.9%) 0.010 ms/op
Iteration   3: 6.572 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.585 ±(99.9%) 0.534 ms/op [Average]
  (min, avg, max) = (6.565, 6.585, 6.619), stdev = 0.029
  CI (99.9%): [6.052, 7.119] (assumes normal distribution)


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
# Warmup Iteration   1: 17.464 ±(99.9%) 0.313 ms/op
# Warmup Iteration   2: 7.455 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 5.878 ±(99.9%) 0.024 ms/op
Iteration   1: 5.683 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   0.524 ms/op
                 createUser·p0.50:   5.325 ms/op
                 createUser·p0.90:   7.062 ms/op
                 createUser·p0.95:   7.987 ms/op
                 createUser·p0.99:   11.796 ms/op
                 createUser·p0.999:  24.175 ms/op
                 createUser·p0.9999: 27.300 ms/op
                 createUser·p1.00:   27.918 ms/op

Iteration   2: 5.490 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   5.186 ms/op
                 createUser·p0.90:   6.750 ms/op
                 createUser·p0.95:   7.537 ms/op
                 createUser·p0.99:   10.666 ms/op
                 createUser·p0.999:  25.231 ms/op
                 createUser·p0.9999: 27.765 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   3: 5.667 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.474 ms/op
                 createUser·p0.50:   5.300 ms/op
                 createUser·p0.90:   7.045 ms/op
                 createUser·p0.95:   8.184 ms/op
                 createUser·p0.99:   11.158 ms/op
                 createUser·p0.999:  21.549 ms/op
                 createUser·p0.9999: 29.732 ms/op
                 createUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170951
  mean =      5.612 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 55655 
    [ 5.000,  7.500) = 104223 
    [ 7.500, 10.000) = 8280 
    [10.000, 12.500) = 1772 
    [12.500, 15.000) = 635 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      6.947 ms/op
     p(95.0000) =      7.897 ms/op
     p(99.0000) =     11.207 ms/op
     p(99.9000) =     23.407 ms/op
     p(99.9900) =     29.146 ms/op
     p(99.9990) =     29.932 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 17.391 ±(99.9%) 0.260 ms/op
# Warmup Iteration   2: 7.185 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.713 ±(99.9%) 0.023 ms/op
Iteration   1: 5.520 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.146 ms/op
                 existUser·p0.50:   5.218 ms/op
                 existUser·p0.90:   6.799 ms/op
                 existUser·p0.95:   7.676 ms/op
                 existUser·p0.99:   10.600 ms/op
                 existUser·p0.999:  15.394 ms/op
                 existUser·p0.9999: 31.051 ms/op
                 existUser·p1.00:   32.014 ms/op

Iteration   2: 5.461 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.097 ms/op
                 existUser·p0.50:   5.063 ms/op
                 existUser·p0.90:   6.906 ms/op
                 existUser·p0.95:   8.233 ms/op
                 existUser·p0.99:   12.141 ms/op
                 existUser·p0.999:  26.378 ms/op
                 existUser·p0.9999: 29.470 ms/op
                 existUser·p1.00:   31.949 ms/op

Iteration   3: 5.425 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.571 ms/op
                 existUser·p0.50:   5.120 ms/op
                 existUser·p0.90:   6.562 ms/op
                 existUser·p0.95:   7.438 ms/op
                 existUser·p0.99:   10.928 ms/op
                 existUser·p0.999:  28.312 ms/op
                 existUser·p0.9999: 33.010 ms/op
                 existUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 175503
  mean =      5.468 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 73038 
    [ 5.000,  7.500) = 91956 
    [ 7.500, 10.000) = 7642 
    [10.000, 12.500) = 1717 
    [12.500, 15.000) = 689 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 88 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.571 ms/op
     p(50.0000) =      5.128 ms/op
     p(90.0000) =      6.734 ms/op
     p(95.0000) =      7.807 ms/op
     p(99.0000) =     11.223 ms/op
     p(99.9000) =     20.283 ms/op
     p(99.9900) =     31.425 ms/op
     p(99.9990) =     33.849 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.620 ±(99.9%) 0.316 ms/op
# Warmup Iteration   2: 7.259 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.042 ±(99.9%) 0.029 ms/op
Iteration   1: 5.789 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   3.015 ms/op
                 getUser·p0.50:   5.349 ms/op
                 getUser·p0.90:   7.283 ms/op
                 getUser·p0.95:   9.044 ms/op
                 getUser·p0.99:   13.386 ms/op
                 getUser·p0.999:  20.012 ms/op
                 getUser·p0.9999: 27.427 ms/op
                 getUser·p1.00:   28.508 ms/op

Iteration   2: 5.688 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.810 ms/op
                 getUser·p0.50:   5.407 ms/op
                 getUser·p0.90:   6.717 ms/op
                 getUser·p0.95:   7.700 ms/op
                 getUser·p0.99:   10.781 ms/op
                 getUser·p0.999:  28.892 ms/op
                 getUser·p0.9999: 59.465 ms/op
                 getUser·p1.00:   60.293 ms/op

Iteration   3: 5.639 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   6.775 ms/op
                 getUser·p0.95:   7.717 ms/op
                 getUser·p0.99:   10.453 ms/op
                 getUser·p0.999:  28.606 ms/op
                 getUser·p0.9999: 38.229 ms/op
                 getUser·p1.00:   40.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 168228
  mean =      5.705 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 42962 
    [ 5.000, 10.000) = 121885 
    [10.000, 15.000) = 2909 
    [15.000, 20.000) = 289 
    [20.000, 25.000) = 27 
    [25.000, 30.000) = 74 
    [30.000, 35.000) = 31 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 30 
    [60.000, 65.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      6.873 ms/op
     p(95.0000) =      8.086 ms/op
     p(99.0000) =     11.502 ms/op
     p(99.9000) =     21.587 ms/op
     p(99.9900) =     58.285 ms/op
     p(99.9990) =     60.204 ms/op
     p(99.9999) =     60.293 ms/op
    p(100.0000) =     60.293 ms/op


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
# Warmup Iteration   1: 20.694 ±(99.9%) 0.319 ms/op
# Warmup Iteration   2: 8.026 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.705 ±(99.9%) 0.027 ms/op
Iteration   1: 6.680 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.687 ms/op
                 listUser·p0.50:   6.357 ms/op
                 listUser·p0.90:   8.069 ms/op
                 listUser·p0.95:   9.257 ms/op
                 listUser·p0.99:   12.681 ms/op
                 listUser·p0.999:  25.695 ms/op
                 listUser·p0.9999: 30.553 ms/op
                 listUser·p1.00:   31.228 ms/op

Iteration   2: 6.464 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   6.177 ms/op
                 listUser·p0.90:   7.553 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   11.705 ms/op
                 listUser·p0.999:  27.430 ms/op
                 listUser·p0.9999: 32.442 ms/op
                 listUser·p1.00:   33.096 ms/op

Iteration   3: 6.742 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.613 ms/op
                 listUser·p0.50:   6.341 ms/op
                 listUser·p0.90:   8.192 ms/op
                 listUser·p0.95:   9.634 ms/op
                 listUser·p0.99:   12.993 ms/op
                 listUser·p0.999:  23.152 ms/op
                 listUser·p0.9999: 44.631 ms/op
                 listUser·p1.00:   45.220 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 144836
  mean =      6.626 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2970 
    [ 5.000, 10.000) = 137172 
    [10.000, 15.000) = 4125 
    [15.000, 20.000) = 223 
    [20.000, 25.000) = 179 
    [25.000, 30.000) = 110 
    [30.000, 35.000) = 25 
    [35.000, 40.000) = 20 
    [40.000, 45.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.290 ms/op
     p(50.0000) =      6.283 ms/op
     p(90.0000) =      7.938 ms/op
     p(95.0000) =      9.142 ms/op
     p(99.0000) =     12.534 ms/op
     p(99.9000) =     25.772 ms/op
     p(99.9900) =     38.736 ms/op
     p(99.9990) =     45.220 ms/op
     p(99.9999) =     45.220 ms/op
    p(100.0000) =     45.220 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.552 ± 3.403  ops/ms
ClientPb.existUser                       thrpt       3   6.125 ± 0.979  ops/ms
ClientPb.getUser                         thrpt       3   5.746 ± 0.438  ops/ms
ClientPb.listUser                        thrpt       3   4.850 ± 1.893  ops/ms
ClientPb.createUser                       avgt       3   5.489 ± 0.814   ms/op
ClientPb.existUser                        avgt       3   5.343 ± 1.872   ms/op
ClientPb.getUser                          avgt       3   5.802 ± 0.684   ms/op
ClientPb.listUser                         avgt       3   6.585 ± 0.534   ms/op
ClientPb.createUser                     sample  170951   5.612 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.524           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.259           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.947           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.897           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.207           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.407           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.146           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.048           ms/op
ClientPb.existUser                      sample  175503   5.468 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.571           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.128           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.734           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.807           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.223           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.283           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.425           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.948           ms/op
ClientPb.getUser                        sample  168228   5.705 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.280           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.374           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.873           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.086           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.502           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.587           ms/op
ClientPb.getUser:getUser·p0.9999        sample          58.285           ms/op
ClientPb.getUser:getUser·p1.00          sample          60.293           ms/op
ClientPb.listUser                       sample  144836   6.626 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.290           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.283           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.938           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.142           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.534           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.772           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.736           ms/op
ClientPb.listUser:listUser·p1.00        sample          45.220           ms/op
