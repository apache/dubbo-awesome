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
# Warmup Iteration   1: 4.368 ops/ms
# Warmup Iteration   2: 12.267 ops/ms
# Warmup Iteration   3: 12.010 ops/ms
Iteration   1: 12.302 ops/ms
Iteration   2: 12.569 ops/ms
Iteration   3: 12.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.426 ±(99.9%) 2.455 ops/ms [Average]
  (min, avg, max) = (12.302, 12.426, 12.569), stdev = 0.135
  CI (99.9%): [9.971, 14.880] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 7.969 ops/ms
# Warmup Iteration   2: 12.785 ops/ms
# Warmup Iteration   3: 12.991 ops/ms
Iteration   1: 12.913 ops/ms
Iteration   2: 12.935 ops/ms
Iteration   3: 13.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.973 ±(99.9%) 1.572 ops/ms [Average]
  (min, avg, max) = (12.913, 12.973, 13.072), stdev = 0.086
  CI (99.9%): [11.401, 14.546] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.923 ops/ms
# Warmup Iteration   2: 12.422 ops/ms
# Warmup Iteration   3: 12.515 ops/ms
Iteration   1: 12.747 ops/ms
Iteration   2: 12.598 ops/ms
Iteration   3: 12.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.687 ±(99.9%) 1.432 ops/ms [Average]
  (min, avg, max) = (12.598, 12.687, 12.747), stdev = 0.079
  CI (99.9%): [11.255, 14.119] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.615 ops/ms
# Warmup Iteration   2: 10.307 ops/ms
# Warmup Iteration   3: 10.587 ops/ms
Iteration   1: 10.356 ops/ms
Iteration   2: 10.595 ops/ms
Iteration   3: 10.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.495 ±(99.9%) 2.271 ops/ms [Average]
  (min, avg, max) = (10.356, 10.495, 10.595), stdev = 0.124
  CI (99.9%): [8.224, 12.766] (assumes normal distribution)


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
# Warmup Iteration   1: 4.402 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.626 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.004 ms/op
Iteration   1: 2.555 ±(99.9%) 0.003 ms/op
Iteration   2: 2.546 ±(99.9%) 0.003 ms/op
Iteration   3: 2.521 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.541 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (2.521, 2.541, 2.555), stdev = 0.018
  CI (99.9%): [2.219, 2.862] (assumes normal distribution)


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
# Warmup Iteration   1: 3.806 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.451 ±(99.9%) 0.004 ms/op
Iteration   2: 2.458 ±(99.9%) 0.004 ms/op
Iteration   3: 2.491 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.467 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (2.451, 2.467, 2.491), stdev = 0.021
  CI (99.9%): [2.078, 2.856] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.038 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.004 ms/op
Iteration   1: 2.536 ±(99.9%) 0.005 ms/op
Iteration   2: 2.516 ±(99.9%) 0.004 ms/op
Iteration   3: 2.540 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.531 ±(99.9%) 0.227 ms/op [Average]
  (min, avg, max) = (2.516, 2.531, 2.540), stdev = 0.012
  CI (99.9%): [2.303, 2.758] (assumes normal distribution)


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
# Warmup Iteration   1: 4.811 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 3.047 ±(99.9%) 0.005 ms/op
Iteration   2: 3.028 ±(99.9%) 0.007 ms/op
Iteration   3: 3.025 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.033 ±(99.9%) 0.212 ms/op [Average]
  (min, avg, max) = (3.025, 3.033, 3.047), stdev = 0.012
  CI (99.9%): [2.821, 3.246] (assumes normal distribution)


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
# Warmup Iteration   1: 4.197 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.694 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.006 ms/op
Iteration   1: 2.494 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  10.785 ms/op
                 createUser·p0.9999: 17.439 ms/op
                 createUser·p1.00:   17.695 ms/op

Iteration   2: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.944 ms/op
                 createUser·p0.999:  10.394 ms/op
                 createUser·p0.9999: 12.894 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  8.680 ms/op
                 createUser·p0.9999: 10.961 ms/op
                 createUser·p1.00:   11.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380984
  mean =      2.517 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 181468 
    [ 2.500,  3.750) = 195055 
    [ 3.750,  5.000) = 3579 
    [ 5.000,  6.250) = 344 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      8.913 ms/op
     p(99.9900) =     15.819 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 3.808 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  8.496 ms/op
                 existUser·p0.9999: 14.104 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.486 ms/op
                 existUser·p0.999:  8.266 ms/op
                 existUser·p0.9999: 13.186 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   3: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.558 ms/op
                 existUser·p0.999:  9.046 ms/op
                 existUser·p0.9999: 11.846 ms/op
                 existUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394412
  mean =      2.431 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 195637 
    [ 2.500,  3.750) = 195709 
    [ 3.750,  5.000) = 2290 
    [ 5.000,  6.250) = 216 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.588 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     13.502 ms/op
     p(99.9990) =     14.257 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 3.895 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.006 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  7.152 ms/op
                 getUser·p0.9999: 13.649 ms/op
                 getUser·p1.00:   14.467 ms/op

Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  9.373 ms/op
                 getUser·p0.9999: 13.722 ms/op
                 getUser·p1.00:   14.549 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.928 ms/op
                 getUser·p0.999:  8.406 ms/op
                 getUser·p0.9999: 11.007 ms/op
                 getUser·p1.00:   11.289 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385310
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 189892 
    [ 2.500,  3.750) = 191237 
    [ 3.750,  5.000) = 3173 
    [ 5.000,  6.250) = 536 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      8.261 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     14.469 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 4.593 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.009 ms/op
Iteration   1: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.793 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 10.568 ms/op
                 listUser·p1.00:   11.108 ms/op

Iteration   2: 3.029 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 10.542 ms/op
                 listUser·p1.00:   11.518 ms/op

Iteration   3: 3.051 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.503 ms/op
                 listUser·p0.9999: 11.977 ms/op
                 listUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316010
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 89766 
    [ 2.500,  3.750) = 184921 
    [ 3.750,  5.000) = 32987 
    [ 5.000,  6.250) = 6731 
    [ 6.250,  7.500) = 804 
    [ 7.500,  8.750) = 234 
    [ 8.750, 10.000) = 309 
    [10.000, 11.250) = 129 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     10.754 ms/op
     p(99.9990) =     12.245 ms/op
     p(99.9999) =     12.386 ms/op
    p(100.0000) =     12.386 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.426 ± 2.455  ops/ms
ClientPb.existUser                       thrpt       3  12.973 ± 1.572  ops/ms
ClientPb.getUser                         thrpt       3  12.687 ± 1.432  ops/ms
ClientPb.listUser                        thrpt       3  10.495 ± 2.271  ops/ms
ClientPb.createUser                       avgt       3   2.541 ± 0.322   ms/op
ClientPb.existUser                        avgt       3   2.467 ± 0.389   ms/op
ClientPb.getUser                          avgt       3   2.531 ± 0.227   ms/op
ClientPb.listUser                         avgt       3   3.033 ± 0.212   ms/op
ClientPb.createUser                     sample  380984   2.517 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.809           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.913           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.819           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.695           ms/op
ClientPb.existUser                      sample  394412   2.431 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.900           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.569           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.502           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.369           ms/op
ClientPb.getUser                        sample  385310   2.489 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.771           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.789           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.261           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.517           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.549           ms/op
ClientPb.listUser                       sample  316010   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.938           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.241           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.754           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.386           ms/op
