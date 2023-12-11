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
# Warmup Iteration   1: 4.778 ops/ms
# Warmup Iteration   2: 12.183 ops/ms
# Warmup Iteration   3: 12.486 ops/ms
Iteration   1: 12.650 ops/ms
Iteration   2: 12.688 ops/ms
Iteration   3: 12.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.668 ±(99.9%) 0.343 ops/ms [Average]
  (min, avg, max) = (12.650, 12.668, 12.688), stdev = 0.019
  CI (99.9%): [12.325, 13.012] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.412 ops/ms
# Warmup Iteration   2: 13.042 ops/ms
# Warmup Iteration   3: 13.104 ops/ms
Iteration   1: 13.182 ops/ms
Iteration   2: 13.143 ops/ms
Iteration   3: 13.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.182 ±(99.9%) 0.710 ops/ms [Average]
  (min, avg, max) = (13.143, 13.182, 13.221), stdev = 0.039
  CI (99.9%): [12.472, 13.891] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.712 ops/ms
# Warmup Iteration   2: 12.876 ops/ms
# Warmup Iteration   3: 12.850 ops/ms
Iteration   1: 12.987 ops/ms
Iteration   2: 13.018 ops/ms
Iteration   3: 12.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.985 ±(99.9%) 0.605 ops/ms [Average]
  (min, avg, max) = (12.951, 12.985, 13.018), stdev = 0.033
  CI (99.9%): [12.380, 13.590] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.606 ops/ms
# Warmup Iteration   2: 10.520 ops/ms
# Warmup Iteration   3: 10.636 ops/ms
Iteration   1: 10.594 ops/ms
Iteration   2: 10.639 ops/ms
Iteration   3: 10.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.571 ±(99.9%) 1.476 ops/ms [Average]
  (min, avg, max) = (10.482, 10.571, 10.639), stdev = 0.081
  CI (99.9%): [9.095, 12.048] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.891 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.475 ±(99.9%) 0.004 ms/op
Iteration   2: 2.526 ±(99.9%) 0.004 ms/op
Iteration   3: 2.479 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.493 ±(99.9%) 0.517 ms/op [Average]
  (min, avg, max) = (2.475, 2.493, 2.526), stdev = 0.028
  CI (99.9%): [1.977, 3.010] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.604 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.429 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.413 ±(99.9%) 0.004 ms/op
Iteration   1: 2.411 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
Iteration   3: 2.415 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.422 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (2.411, 2.422, 2.440), stdev = 0.016
  CI (99.9%): [2.136, 2.709] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.909 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.003 ms/op
Iteration   1: 2.444 ±(99.9%) 0.004 ms/op
Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
Iteration   3: 2.434 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.443 ±(99.9%) 0.149 ms/op [Average]
  (min, avg, max) = (2.434, 2.443, 2.450), stdev = 0.008
  CI (99.9%): [2.294, 2.591] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.777 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.005 ms/op
Iteration   1: 2.997 ±(99.9%) 0.005 ms/op
Iteration   2: 3.001 ±(99.9%) 0.005 ms/op
Iteration   3: 3.019 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.006 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (2.997, 3.006, 3.019), stdev = 0.011
  CI (99.9%): [2.799, 3.212] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.988 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.006 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.683 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  9.939 ms/op
                 createUser·p0.9999: 13.372 ms/op
                 createUser·p1.00:   14.451 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.486 ms/op
                 createUser·p0.999:  9.503 ms/op
                 createUser·p0.9999: 12.405 ms/op
                 createUser·p1.00:   12.730 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  8.039 ms/op
                 createUser·p0.9999: 11.520 ms/op
                 createUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385668
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 187069 
    [ 2.500,  3.750) = 195430 
    [ 3.750,  5.000) = 2389 
    [ 5.000,  6.250) = 295 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      8.902 ms/op
     p(99.9900) =     13.091 ms/op
     p(99.9990) =     14.046 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.589 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.440 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
Iteration   1: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.355 ms/op
                 existUser·p0.999:  5.169 ms/op
                 existUser·p0.9999: 12.989 ms/op
                 existUser·p1.00:   13.222 ms/op

Iteration   2: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.866 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  6.579 ms/op
                 existUser·p0.9999: 12.985 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   3: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  7.663 ms/op
                 existUser·p0.9999: 11.696 ms/op
                 existUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394643
  mean =      2.430 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 196461 
    [ 2.500,  3.750) = 195632 
    [ 3.750,  5.000) = 1839 
    [ 5.000,  6.250) = 269 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.465 ms/op
     p(99.9000) =      6.267 ms/op
     p(99.9900) =     12.821 ms/op
     p(99.9990) =     13.655 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.825 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.559 ms/op
                 getUser·p0.999:  5.800 ms/op
                 getUser·p0.9999: 13.664 ms/op
                 getUser·p1.00:   14.434 ms/op

Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.670 ms/op
                 getUser·p0.999:  8.750 ms/op
                 getUser·p0.9999: 13.255 ms/op
                 getUser·p1.00:   14.172 ms/op

Iteration   3: 2.533 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  9.110 ms/op
                 getUser·p0.9999: 11.633 ms/op
                 getUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384592
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 189572 
    [ 2.500,  3.750) = 190145 
    [ 3.750,  5.000) = 3399 
    [ 5.000,  6.250) = 927 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 124 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      9.100 ms/op
     p(99.9900) =     13.272 ms/op
     p(99.9990) =     14.020 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.946 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.009 ms/op
Iteration   1: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.592 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.191 ms/op
                 listUser·p0.9999: 11.048 ms/op
                 listUser·p1.00:   11.960 ms/op

Iteration   2: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 10.723 ms/op
                 listUser·p1.00:   11.370 ms/op

Iteration   3: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.845 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.033 ms/op
                 listUser·p0.9999: 10.768 ms/op
                 listUser·p1.00:   11.158 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316945
  mean =      3.026 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 89964 
    [ 2.500,  3.750) = 186400 
    [ 3.750,  5.000) = 33200 
    [ 5.000,  6.250) = 5897 
    [ 6.250,  7.500) = 698 
    [ 7.500,  8.750) = 231 
    [ 8.750, 10.000) = 303 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     10.830 ms/op
     p(99.9990) =     11.646 ms/op
     p(99.9999) =     11.960 ms/op
    p(100.0000) =     11.960 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.668 ± 0.343  ops/ms
ClientPb.existUser                       thrpt       3  13.182 ± 0.710  ops/ms
ClientPb.getUser                         thrpt       3  12.985 ± 0.605  ops/ms
ClientPb.listUser                        thrpt       3  10.571 ± 1.476  ops/ms
ClientPb.createUser                       avgt       3   2.493 ± 0.517   ms/op
ClientPb.existUser                        avgt       3   2.422 ± 0.287   ms/op
ClientPb.getUser                          avgt       3   2.443 ± 0.149   ms/op
ClientPb.listUser                         avgt       3   3.006 ± 0.207   ms/op
ClientPb.createUser                     sample  385668   2.487 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.683           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.015           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.645           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.902           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.091           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.514           ms/op
ClientPb.existUser                      sample  394643   2.430 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.849           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.267           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.821           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.943           ms/op
ClientPb.getUser                        sample  384592   2.494 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.849           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.100           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.272           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.434           ms/op
ClientPb.listUser                       sample  316945   3.026 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.592           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.142           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.830           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.960           ms/op
