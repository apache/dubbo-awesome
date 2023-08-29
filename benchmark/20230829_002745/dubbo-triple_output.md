# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.459 ops/ms
# Warmup Iteration   2: 6.284 ops/ms
# Warmup Iteration   3: 8.859 ops/ms
Iteration   1: 9.760 ops/ms
Iteration   2: 9.699 ops/ms
Iteration   3: 9.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.645 ±(99.9%) 2.725 ops/ms [Average]
  (min, avg, max) = (9.476, 9.645, 9.760), stdev = 0.149
  CI (99.9%): [6.920, 12.371] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.206 ops/ms
# Warmup Iteration   2: 8.797 ops/ms
# Warmup Iteration   3: 10.063 ops/ms
Iteration   1: 10.064 ops/ms
Iteration   2: 10.073 ops/ms
Iteration   3: 10.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.135 ±(99.9%) 2.115 ops/ms [Average]
  (min, avg, max) = (10.064, 10.135, 10.269), stdev = 0.116
  CI (99.9%): [8.021, 12.250] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.597 ops/ms
# Warmup Iteration   2: 9.050 ops/ms
# Warmup Iteration   3: 9.522 ops/ms
Iteration   1: 9.909 ops/ms
Iteration   2: 10.204 ops/ms
Iteration   3: 9.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.023 ±(99.9%) 2.888 ops/ms [Average]
  (min, avg, max) = (9.909, 10.023, 10.204), stdev = 0.158
  CI (99.9%): [7.136, 12.911] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.181 ops/ms
# Warmup Iteration   2: 7.483 ops/ms
# Warmup Iteration   3: 8.144 ops/ms
Iteration   1: 8.053 ops/ms
Iteration   2: 8.242 ops/ms
Iteration   3: 8.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.138 ±(99.9%) 1.751 ops/ms [Average]
  (min, avg, max) = (8.053, 8.138, 8.242), stdev = 0.096
  CI (99.9%): [6.388, 9.889] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.662 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.004 ms/op
Iteration   1: 3.311 ±(99.9%) 0.005 ms/op
Iteration   2: 3.188 ±(99.9%) 0.005 ms/op
Iteration   3: 3.156 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.218 ±(99.9%) 1.491 ms/op [Average]
  (min, avg, max) = (3.156, 3.218, 3.311), stdev = 0.082
  CI (99.9%): [1.727, 4.709] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.213 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.422 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.003 ms/op
Iteration   1: 3.162 ±(99.9%) 0.005 ms/op
Iteration   2: 3.191 ±(99.9%) 0.005 ms/op
Iteration   3: 3.203 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.185 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (3.162, 3.185, 3.203), stdev = 0.021
  CI (99.9%): [2.797, 3.574] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.038 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.590 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.003 ms/op
Iteration   1: 3.325 ±(99.9%) 0.003 ms/op
Iteration   2: 3.254 ±(99.9%) 0.004 ms/op
Iteration   3: 3.349 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.309 ±(99.9%) 0.898 ms/op [Average]
  (min, avg, max) = (3.254, 3.309, 3.349), stdev = 0.049
  CI (99.9%): [2.411, 4.207] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.594 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.003 ms/op
Iteration   1: 3.893 ±(99.9%) 0.004 ms/op
Iteration   2: 3.866 ±(99.9%) 0.006 ms/op
Iteration   3: 3.820 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.860 ±(99.9%) 0.679 ms/op [Average]
  (min, avg, max) = (3.820, 3.860, 3.893), stdev = 0.037
  CI (99.9%): [3.181, 4.538] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.889 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.010 ms/op
Iteration   1: 3.393 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.310 ms/op
                 createUser·p0.999:  16.616 ms/op
                 createUser·p0.9999: 24.510 ms/op
                 createUser·p1.00:   25.166 ms/op

Iteration   2: 3.234 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.368 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  12.304 ms/op
                 createUser·p0.9999: 20.549 ms/op
                 createUser·p1.00:   21.234 ms/op

Iteration   3: 3.303 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  16.267 ms/op
                 createUser·p0.9999: 21.722 ms/op
                 createUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290196
  mean =      3.309 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18473 
    [ 2.500,  5.000) = 263779 
    [ 5.000,  7.500) = 6471 
    [ 7.500, 10.000) = 798 
    [10.000, 12.500) = 299 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     15.936 ms/op
     p(99.9900) =     22.675 ms/op
     p(99.9990) =     24.756 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.312 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.376 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.009 ms/op
Iteration   1: 3.248 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  13.173 ms/op
                 existUser·p0.9999: 19.864 ms/op
                 existUser·p1.00:   21.135 ms/op

Iteration   2: 3.288 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.329 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  14.582 ms/op
                 existUser·p0.9999: 22.324 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   3: 3.237 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.411 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   6.144 ms/op
                 existUser·p0.999:  10.961 ms/op
                 existUser·p0.9999: 22.057 ms/op
                 existUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294611
  mean =      3.257 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14148 
    [ 2.500,  5.000) = 272052 
    [ 5.000,  7.500) = 7219 
    [ 7.500, 10.000) = 666 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     22.874 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.791 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.475 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.011 ms/op
Iteration   1: 3.257 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.364 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  10.469 ms/op
                 getUser·p0.9999: 22.228 ms/op
                 getUser·p1.00:   23.658 ms/op

Iteration   2: 3.272 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.252 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  21.016 ms/op
                 getUser·p0.9999: 28.777 ms/op
                 getUser·p1.00:   29.557 ms/op

Iteration   3: 3.388 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.481 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  10.322 ms/op
                 getUser·p0.9999: 19.656 ms/op
                 getUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290450
  mean =      3.304 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10262 
    [ 2.500,  5.000) = 271709 
    [ 5.000,  7.500) = 7111 
    [ 7.500, 10.000) = 904 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.252 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     12.444 ms/op
     p(99.9900) =     26.274 ms/op
     p(99.9990) =     29.426 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.408 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.321 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.013 ms/op
Iteration   1: 3.921 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   7.766 ms/op
                 listUser·p0.999:  16.269 ms/op
                 listUser·p0.9999: 21.016 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   2: 3.785 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 15.286 ms/op
                 listUser·p1.00:   15.499 ms/op

Iteration   3: 3.909 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.058 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.758 ms/op
                 listUser·p0.999:  12.517 ms/op
                 listUser·p0.9999: 21.053 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247734
  mean =      3.871 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 238043 
    [ 5.000,  7.500) = 6707 
    [ 7.500, 10.000) = 1966 
    [10.000, 12.500) = 517 
    [12.500, 15.000) = 276 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      7.730 ms/op
     p(99.9000) =     13.713 ms/op
     p(99.9900) =     20.611 ms/op
     p(99.9990) =     22.173 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.645 ± 2.725  ops/ms
ClientPb.existUser                       thrpt       3  10.135 ± 2.115  ops/ms
ClientPb.getUser                         thrpt       3  10.023 ± 2.888  ops/ms
ClientPb.listUser                        thrpt       3   8.138 ± 1.751  ops/ms
ClientPb.createUser                       avgt       3   3.218 ± 1.491   ms/op
ClientPb.existUser                        avgt       3   3.185 ± 0.388   ms/op
ClientPb.getUser                          avgt       3   3.309 ± 0.898   ms/op
ClientPb.listUser                         avgt       3   3.860 ± 0.679   ms/op
ClientPb.createUser                     sample  290196   3.309 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.927           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.136           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.936           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.675           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.166           ms/op
ClientPb.existUser                      sample  294611   3.257 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.069           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.054           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.565           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.053           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.938           ms/op
ClientPb.getUser                        sample  290450   3.304 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.252           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.670           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.578           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.444           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.274           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.557           ms/op
ClientPb.listUser                       sample  247734   3.871 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.924           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.715           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.730           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.713           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.611           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.381           ms/op
