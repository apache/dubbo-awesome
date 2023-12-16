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
# Warmup Iteration   1: 4.832 ops/ms
# Warmup Iteration   2: 12.106 ops/ms
# Warmup Iteration   3: 12.358 ops/ms
Iteration   1: 12.611 ops/ms
Iteration   2: 12.705 ops/ms
Iteration   3: 12.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.663 ±(99.9%) 0.876 ops/ms [Average]
  (min, avg, max) = (12.611, 12.663, 12.705), stdev = 0.048
  CI (99.9%): [11.787, 13.540] (assumes normal distribution)


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
# Warmup Iteration   1: 8.289 ops/ms
# Warmup Iteration   2: 13.209 ops/ms
# Warmup Iteration   3: 13.220 ops/ms
Iteration   1: 13.237 ops/ms
Iteration   2: 13.267 ops/ms
Iteration   3: 13.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.248 ±(99.9%) 0.304 ops/ms [Average]
  (min, avg, max) = (13.237, 13.248, 13.267), stdev = 0.017
  CI (99.9%): [12.944, 13.552] (assumes normal distribution)


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
# Warmup Iteration   1: 8.220 ops/ms
# Warmup Iteration   2: 12.678 ops/ms
# Warmup Iteration   3: 12.669 ops/ms
Iteration   1: 12.927 ops/ms
Iteration   2: 12.901 ops/ms
Iteration   3: 12.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.921 ±(99.9%) 0.343 ops/ms [Average]
  (min, avg, max) = (12.901, 12.921, 12.937), stdev = 0.019
  CI (99.9%): [12.578, 13.264] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.732 ops/ms
# Warmup Iteration   2: 10.661 ops/ms
# Warmup Iteration   3: 10.705 ops/ms
Iteration   1: 10.559 ops/ms
Iteration   2: 10.731 ops/ms
Iteration   3: 10.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.659 ±(99.9%) 1.633 ops/ms [Average]
  (min, avg, max) = (10.559, 10.659, 10.731), stdev = 0.090
  CI (99.9%): [9.026, 12.293] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.985 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.003 ms/op
Iteration   1: 2.516 ±(99.9%) 0.004 ms/op
Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
Iteration   3: 2.529 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.520 ±(99.9%) 0.152 ms/op [Average]
  (min, avg, max) = (2.514, 2.520, 2.529), stdev = 0.008
  CI (99.9%): [2.368, 2.672] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.609 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.421 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.004 ms/op
Iteration   1: 2.414 ±(99.9%) 0.003 ms/op
Iteration   2: 2.418 ±(99.9%) 0.004 ms/op
Iteration   3: 2.422 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.418 ±(99.9%) 0.070 ms/op [Average]
  (min, avg, max) = (2.414, 2.418, 2.422), stdev = 0.004
  CI (99.9%): [2.348, 2.488] (assumes normal distribution)


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
# Warmup Iteration   1: 3.737 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.004 ms/op
Iteration   1: 2.463 ±(99.9%) 0.004 ms/op
Iteration   2: 2.445 ±(99.9%) 0.004 ms/op
Iteration   3: 2.448 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.452 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (2.445, 2.452, 2.463), stdev = 0.010
  CI (99.9%): [2.278, 2.626] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.823 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.005 ms/op
Iteration   1: 2.981 ±(99.9%) 0.004 ms/op
Iteration   2: 2.983 ±(99.9%) 0.005 ms/op
Iteration   3: 2.994 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.986 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (2.981, 2.986, 2.994), stdev = 0.007
  CI (99.9%): [2.859, 3.112] (assumes normal distribution)


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
# Warmup Iteration   1: 4.058 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.687 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.656 ms/op
                 createUser·p0.999:  11.506 ms/op
                 createUser·p0.9999: 13.276 ms/op
                 createUser·p1.00:   13.681 ms/op

Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.680 ms/op
                 createUser·p0.999:  10.023 ms/op
                 createUser·p0.9999: 12.541 ms/op
                 createUser·p1.00:   12.911 ms/op

Iteration   3: 2.580 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.932 ms/op
                 createUser·p0.999:  8.349 ms/op
                 createUser·p0.9999: 11.043 ms/op
                 createUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374895
  mean =      2.558 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 178329 
    [ 2.500,  3.750) = 192725 
    [ 3.750,  5.000) = 3065 
    [ 5.000,  6.250) = 283 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 79 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.646 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      8.425 ms/op
     p(99.9900) =     13.034 ms/op
     p(99.9990) =     13.500 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


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
# Warmup Iteration   1: 3.673 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
Iteration   1: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.375 ms/op
                 existUser·p0.999:  7.853 ms/op
                 existUser·p0.9999: 14.089 ms/op
                 existUser·p1.00:   14.828 ms/op

Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.805 ms/op
                 existUser·p0.999:  5.857 ms/op
                 existUser·p0.9999: 13.337 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.908 ms/op
                 existUser·p0.999:  8.411 ms/op
                 existUser·p0.9999: 11.862 ms/op
                 existUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388145
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 190636 
    [ 2.500,  3.750) = 193958 
    [ 3.750,  5.000) = 2370 
    [ 5.000,  6.250) = 740 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      6.502 ms/op
     p(99.9900) =     13.812 ms/op
     p(99.9990) =     14.659 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


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
# Warmup Iteration   1: 3.770 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.006 ms/op
Iteration   1: 2.430 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   2.953 ms/op
                 getUser·p0.95:   3.047 ms/op
                 getUser·p0.99:   3.498 ms/op
                 getUser·p0.999:  5.945 ms/op
                 getUser·p0.9999: 15.991 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.787 ms/op
                 getUser·p0.999:  6.988 ms/op
                 getUser·p0.9999: 12.846 ms/op
                 getUser·p1.00:   13.156 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   4.080 ms/op
                 getUser·p0.999:  7.925 ms/op
                 getUser·p0.9999: 10.373 ms/op
                 getUser·p1.00:   10.502 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389821
  mean =      2.460 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 194911 
    [ 2.500,  3.750) = 190825 
    [ 3.750,  5.000) = 3139 
    [ 5.000,  6.250) = 482 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 134 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      7.718 ms/op
     p(99.9900) =     13.075 ms/op
     p(99.9990) =     16.746 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 4.576 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.008 ms/op
Iteration   1: 3.011 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  8.615 ms/op
                 listUser·p0.9999: 11.354 ms/op
                 listUser·p1.00:   11.633 ms/op

Iteration   2: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.928 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.880 ms/op
                 listUser·p0.9999: 11.257 ms/op
                 listUser·p1.00:   13.173 ms/op

Iteration   3: 2.986 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  8.929 ms/op
                 listUser·p0.9999: 10.376 ms/op
                 listUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319726
  mean =      3.000 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 95685 
    [ 2.500,  3.750) = 184785 
    [ 3.750,  5.000) = 31926 
    [ 5.000,  6.250) = 5931 
    [ 6.250,  7.500) = 604 
    [ 7.500,  8.750) = 272 
    [ 8.750, 10.000) = 222 
    [10.000, 11.250) = 159 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     11.158 ms/op
     p(99.9990) =     11.659 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.663 ± 0.876  ops/ms
ClientPb.existUser                       thrpt       3  13.248 ± 0.304  ops/ms
ClientPb.getUser                         thrpt       3  12.921 ± 0.343  ops/ms
ClientPb.listUser                        thrpt       3  10.659 ± 1.633  ops/ms
ClientPb.createUser                       avgt       3   2.520 ± 0.152   ms/op
ClientPb.existUser                        avgt       3   2.418 ± 0.070   ms/op
ClientPb.getUser                          avgt       3   2.452 ± 0.174   ms/op
ClientPb.listUser                         avgt       3   2.986 ± 0.127   ms/op
ClientPb.createUser                     sample  374895   2.558 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.882           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.646           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.425           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.034           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.681           ms/op
ClientPb.existUser                      sample  388145   2.471 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.666           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.502           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.812           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.828           ms/op
ClientPb.getUser                        sample  389821   2.460 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.781           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.986           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.718           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.075           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.039           ms/op
ClientPb.listUser                       sample  319726   3.000 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.885           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.077           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.158           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.173           ms/op
